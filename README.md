# python1
import random
when = ['A few years ago', 'Yesterday', 'Last night', 'A long time ago', 'On 20th Jan']
who = ['a rabbit', 'an elephant', 'a mouse', 'a turtle', 'a cat']
name = ['Ali', 'Miriam','daniel', 'Hoouk', 'Starwalker']
residence = ['Barcelona','India', 'Germany', 'Venice', 'England']
went = ['cinema', 'university','seminar', 'school', 'laundry']
happened = ['made a lot of friends','Eats a burger', 'found a secret key', 'solved a mistery', 'wrote a book']
with1 = ['f amily','friends','nieghbour','teacher']
print(random.choice(when) + ', ' + random.choice(who) + ' whose name was' + ' ' + random.choice(name) + ' ' + 'lived in ' + random.choice(residence) + ', went to the ' + random.choice(went) + ' with ' + random.choice(with1) + ' and ' + random.choice(happened))
