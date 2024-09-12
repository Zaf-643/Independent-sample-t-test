# Independent-sample-t-test
mc1 <- c(23,32,23,14,53,53,23)
mc2 <- c(21,22,33,34,15,54,34)
mc3 <- c(33,13,543,34,13,45,33)

var.test(x = mc1, y = mc2)
t.test(x = mc1, y = mc2, var.equal = TRUE)


var.test(x = mc1, y = mc3)
t.test(x = mc1, y = mc3, var.equal = FALSE)


var.test(x = mc2, y = mc3)
t.test(x = mc2, y = mc3, var.equal = FALSE)
