练习16.38：当我们调用make_shared(参加12.1.1节，第401页)时，必须提供一个显式模板实参。解释为什么需要显式模板实参以及它是如何使用的。

---

make_shared的参数是构造类型对象的参数列表（可为空），不能由此推断出对象的类型，因此要提供显式模板实参表明返回值。
