Performance Tips


  Ruby
  - upgrade to latest, ruby 2.4
  - any? & reject methods nice
  - Cuba framework, really lightweight (hanami is another)


  Rails
  - Event.first.registration_ids, not pluck...
  - eager load, dont trigger n+1 queries
  - `touch: true`, helps with russian doll caching (things that get updated+displayed a lot basecamp uses it for)
  - Dont loop thru, just render using `collection: books` for a lot of things


  *stay in active record as long as possible
  - editor in mysql? postgres is in \e
  * explain, shows the 'cost'
  * merge method helps keep things dry, 


  * polymorphic gem?
  * subscribe to ruby weekly


  Apache bench, nice easy request benchmark

  * null false on database, as well as validation

