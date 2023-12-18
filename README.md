### Hi there 👋

`aboutMe.rb`

```ruby
require 'job'

me = User.create(
  name: "Robi Maliqi",
  job: "Full-Stack Developer",
  dob: Date.new(1993, 7, 1),
  country: "United Kingdom",

  url: "https://www.robicodes.com/",
  coding_languages: [
    "Ruby",
    "JavaScript",
    "Ruby on Rails",
    "Express",
    "React",
    "Typescript"
  ],

  learning_new_skills: true,
  hobbies: [
    "Hiking",
    "Chasing sunsets/sunrises",
    "Chess"
  ]
)

