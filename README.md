class Sy < Person
  def initialize
    @name = 'Sy Rashid'
    @age = 33
    @work = [ 'ARTSVP', 'MangoTree Dev' ]
    @education = [ 'Georgia Tech MSCS', 'Le Wagon', 'HBX/HBS', 'Georgia Tech BSNRE' ]
    @hobbies = [ 'Skydiving', 'Snowboarding', 'Burritos' ]
  end

  def languages
    {
      human: [ 'English', 'Bengali', 'Portuguese', 'Spanish' ],
      programming: [ 'Ruby', 'Python', 'Javascript', 'SQL', 'C' ]
     }
  end

  def current_location
    'Lisbon, PT'
  end

  def next_locations
    [ 'Chamonix, FR' ]
  end

  def currently
    {
      studying: [ 'Natural Language Processing', 'Deep Learning', 'Language of Proofs' ],
      reading: [ 'The Moral Animal', 'Discrete Mathmatics and Its Applications' ],
      tinkering: [ 'PR Stacking (Graphite)', 'Quant Trading', 'Frontside Shifty' ]
     }
  end
end
