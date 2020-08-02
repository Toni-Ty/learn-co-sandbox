Hi

You've opened the IDE Sandbox. 🎉

The Sandbox is an environment that you can access on "readme" and "code-along" lessons in Learn. It's a great place to experiment with code when you're not working on a "lab" (labs open the IDE In Browser).

The work you do in the Sandbox will be saved from lesson to lesson, and is automatically saved on your behalf to a repository in your GitHub account called `learn-co-sandbox`.

Please DO NOT touch this repository in GitHub, as it will affect your Sandbox experience, and potentially cause your work to be out of sync.

To learn more about the Sandbox, please visit http://help.learn.co/ide-in-browser#sandbox.

first_number = 7
second_number = 14
sum = first_number + second_number
puts sum


current_president = "Barack O"
puts "In 2016, the president was # {current_president}."
# Practicename created


def self.all 
  @@all
end 
 
 
 Person.new("Grace Hopper")
 
grace_hopper == Person.all.find { |person| person.name == "Grace Hopper"}

def self.find_by_name(name)
  @all.find{ |p| p.name == "Grace Hopper"}
 
 end
 
 grace_hopper = Person.find_by_name("Grace Hopper")
 
 


def self.new_from_csv(csv_data)
rows = csv_data.split("\n")
people = rows.collect do |row|
data = row.split(",")
name = data[0]
age = data[1]
company = data[2]

person = self.new

person = Person.new
person.name = name
person.age = age
person.company = company
person

people = Person.new_from_csv(csv_data)

people >> Person.new_from_csv()
people.flatten
people
end

people


class Dog 

  attr_accessor :dog, :name
  
  
  def initialize(name)
    @name = name
  end
  
end
  
  
  
def dog_name=(dog_name)
  @dog_name = dog_name
end

def dog_name
  @dog_name
end


class Album

@@album_count = 0

def initialize
  @@album_count += 1
end

def self.album_counter
  @@album_count
  end
end


Album.new 
Album.new
Album.new 
Album.new

Album.album_counter

























 