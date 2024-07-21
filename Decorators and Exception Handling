# entri-assignment
Decorators and Exception Handling
def greet(func):
    def wrapper(*args, **kwargs):
        print("Hello, welcome to the function!")
        return func(*args, **kwargs)
    return wrapper

@greet
def say_hello(name):
    print(f"Hello, {name}!")

say_hello("Alice")
