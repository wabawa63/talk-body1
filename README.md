# talk-body1
print "Quel est votre prénom ?"
prenom = gets.chomp
prenom.capitalize!

print "Quel est votre nom de famille ?"
nom = gets.chomp
nom.capitalize!

print "De quelle ville venez-vous ?"
ville = gets.chomp
ville.capitalize!

print "De quel pays venez-vous ?"
pays  = gets.chomp
pays.upcase!

puts "Vous vous appelez #{prenom} #{nom} et vous venez de #{ville}, #{pays}!"
