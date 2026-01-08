
    def  addieren(a, b):
        return a + b

    def subtrahieren(a, b):
        return a - b

    def multiplizieren(a, b):
        return a * b

    def dividieren(a, b):
        return a / b
        if b == 0:
            print("Division durch Null ist nicht möglich!")


    print("Wähle eine Operation: ")
    print("1. Addition")
    print("2. Subtraktion")
    print("3. Multiplikation")
    print("4. Division")
    wahl = input("Gib deine Wahl ein (1-4): ")

    zahl1 = float(input("Gib die erste Zahl ein: "))
    zahl2 = float(input("Gib die zweite Zahl ein: "))
    if wahl == '1':
       print(zahl1, "+", zahl2, "=", addieren(zahl1, zahl2))
    elif wahl == '2':
       print(zahl1, "-", zahl2, "=", subtrahieren(zahl1, zahl2))
    elif wahl == '3':
       print(zahl1, "*", zahl2, "=", multiplizieren(zahl1, zahl2))
    elif wahl == '4':
       print(zahl1, "/", zahl2, "=", dividieren(zahl1, zahl2))
    else:
       print("Ungültige Eingabe")
