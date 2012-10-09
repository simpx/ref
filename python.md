Python Quick Reference

Comment
---------

    #single line comment
    """
    Here is
    a
    multiline
    comment
    """
Function
---------

    def say_hello():
        print "Hello World!"
    
    def plus(a, b=1):
        num = a + b
        print num
    
    def func(a, *args, **kwargs):
        print a
        print args
        print kwargs

Array & Tuple & Dict
---------
    races = ('pandaren', 'worgan', 'dwarf')  #tuple
    song = ["do", "re", "mi", "fa", "so"]    #array
    kids = {'brother': {'name': 'Max',       #dict
                        'age': 11},
            'sister':  {'name': 'Ida',
                        'age': 9}}

Conditional Expressions
---------
    if weekdays and rain:
      bring(umbrella)
    elif saturday:
      stay()
    else:
      play()