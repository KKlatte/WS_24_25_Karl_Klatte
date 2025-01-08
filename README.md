# WS_24_25_Karl_Klatte

Aufgabe 1

def string_to_array(your_string):
    woerter=your_string.split()
    return woerter
    pass


Aufgabe 2

def maskify(your_str):
    if len(your_str) > 4:
        return '#'* (len(your_str)-4) + your_str[-4:]
    else:
        return your_string
    pass



Aufgabe 3

def basic_op(operator, value1, value2):
    if operation == 'addieren':
        return value1 + value2
    elif operation == 'subtrahieren':
        return value1 - value2
    elif operation == 'multiplizieren':
        return value1 * value2
    elif operation == 'dividieren':
          if value2 != 0:
            return value1 / value2
        else:
            return "Fehler: Division durch null!"
    else:
        return "Unbekannte Operation!"
    pass


  Aufgabe 4
