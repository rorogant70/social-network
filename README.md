# social-network
class User:
    def __init__(self, name, password):
        self.name = name
        self.password = password
    def add_user(self, connection):
        self.connection = []
        #self.email = input('enter email')
        #if user + user then connect to network
    # Define the fields and methods for your object here.
#init is an intalizer that constructs a new object
class Network:
    # Define the fields and methods for your object here.
    def __init__ (self):
        people = Network
        self.people = []
        #self.connection = connection
    #def __init__(self, users, nameinput):
        #self.users = users
        #self.nameinput = nameinput
        #self.useradd = useradd
    #def __init__(self, user):
        #if user + user
            #useradd
def main():
    #person = User(self, name, password)
    done = False
    while (not done):
        welcome = input("Welcome human! Type 'u' to create a user, 'pu' to print users, 'c' to create a connection, 'pc' to print connections, and 'e' for exit.")
#createUser = Type 'u' to create a user
        if welcome == "u":
            name = input("Enter username")
            password = input("Enter password")

        if welcome == "pu":
            for x in [user]:
                print(x)
            person.User()
            print(self.user)

        if welcome == "c":
            connectionUser = input("Enter connection name")

        if welcome == "pc":
            for y in [connection]:
                print(y)
            people.Network()
            print(Network.connection)

        if welcome == "e":
            done = True
    print("Goodbye")
    #useradd = input("Enter username")
    # Define the program flow for your user interface here.
# Runs your program.
if __name__ == '__main__':
    main()
