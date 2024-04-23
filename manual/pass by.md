what is pass by?

pass by value

const x = 5

let y = 10

y = x

console.log(y)


pass by refference

const obj1 = {
    name:"ton",
    age:20,
    major:"DG"
}

const obj2 = obj1

obj2.name = "Kowit"

console.log(obj1.name)