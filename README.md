# rails-useful-resources
collection of useful links to blogs, articles, stackoverflow questions etc. which I collected during learning ruby on rails

## For beginners

guides: http://guides.rubyonrails.org/

Michael Hartl book/tutorial: https://www.railstutorial.org/book

## How to learn rails

https://medium.com/@javier_noris/an-outline-to-learning-to-code-in-1-year-572a1a78fa62#.b2jcohyze

## Style guides

ruby: https://github.com/bbatsov/ruby-style-guide

rails: https://github.com/bbatsov/rails-style-guide

## Generators

rails generate command: http://www.korenlc.com/rails-generate-model-vs-resourse-vs-scaffold/

## Active Record

what is index in database: http://stackoverflow.com/questions/1108/how-does-database-indexing-work

take vs limit 1: http://stackoverflow.com/questions/19123293/difference-between-activerecords-finder-methods-take-vs-limit1

size vs count: http://stackoverflow.com/questions/6083219/activerecord-size-vs-count

self references: http://stackoverflow.com/questions/6097288/how-can-i-do-self-reference-with-ruby-on-rails

pluck docs: http://apidock.com/rails/ActiveRecord/Calculations/pluck

collect vs pluck: http://stackoverflow.com/questions/12176102/what-is-the-difference-between-pluck-and-collect-in-rails

sql tree structure1: https://www.leighhalliday.com/tree-structures-in-your-rails-models

sql tree structure2: https://hashrocket.com/blog/posts/recursive-sql-in-activerecord

mongo db tree structure: https://www.codementor.io/mongodb/tutorial/storing-tree-structures-in-mongodb-example-code

### Migrations

rename column: http://stackoverflow.com/questions/1992019/how-can-i-rename-a-database-column-in-a-ruby-on-rails-migration

drop table: http://stackoverflow.com/questions/4020131/rails-db-migration-how-to-drop-a-table

drop columns: http://stackoverflow.com/questions/2831059/how-to-drop-columns-using-rails-migration

column types: http://stackoverflow.com/questions/11889048/is-there-documentation-for-the-rails-column-types

### Query

scopes: http://stackoverflow.com/questions/4869994/what-is-scope-named-scope-in-rails

order by count of has_many :through association: http://elegantbrew.tumblr.com/post/118454164260/order-by-count-of-hasmany-through-association-in

### Associations

many to many associations in rails: http://joshfrankel.me/blog/2016/how-to/create-a-many-to-many-activerecord-association-in-ruby-on-rails/

polymorphic associations: https://gorails.com/episodes/comments-with-polymorphic-associations

### Includes

docs: http://apidock.com/rails/ActiveRecord/QueryMethods/includes

includes vs joins: http://tomdallimore.com/blog/includes-vs-joins-in-rails-when-and-where/

### N+1 Problem

what is n+1 query problem: http://stackoverflow.com/questions/97197/what-is-the-n1-selects-issue

how to diagnose n+1 problem: http://jakeyesbeck.com/2016/04/17/how-to-diagnose-ruby-on-rails-n-plus-1-query-problems/

## Routes / Pretty URLs

docs: http://api.rubyonrails.org/classes/ActionDispatch/Routing.html

a lot about pretty urls: https://gist.github.com/jcasimir/1209730

friendly_it gem: http://olivierlacan.com/posts/migrating-an-ad-hoc-url-slug-system-to-friendly-id/

## Helpers

helper example: http://www.rails-dev.com/custom-view-helpers-in-rails-4

designing helpers: http://techspry.com/ruby_and_rails/designing-helpers-in-ruby-on-rails/

## Concerns

docs: http://api.rubyonrails.org/classes/ActiveSupport/Concern.html

https://richonrails.com/articles/rails-4-code-concerns-in-active-record-models

https://gist.github.com/dhh/1014971

https://signalvnoise.com/posts/3372-put-chubby-models-on-a-diet-with-concerns

http://stackoverflow.com/questions/14541823/how-to-use-concerns-in-rails-4

http://elegantbrew.tumblr.com/post/70990048275/controller-concerns-in-rails-4

## Nested forms

http://mendelk.github.io/blog/2013/07/18/patterns-for-saving-associated-model-data-in-rails/

https://www.sitepoint.com/complex-rails-forms-with-nested-attributes/

http://www.createdbypete.com/articles/working-with-nested-forms-and-a-many-to-many-association-in-rails-4/

http://railscasts.com/episodes/196-nested-model-form-part-1

http://homeonrails.com/2012/10/validating-nested-associations-in-rails/

http://stackoverflow.com/questions/2595969/validate-number-of-nested-attributes

http://stackoverflow.com/questions/18436777/how-should-i-use-rails-and-simple-form-for-nested-resources

http://stackoverflow.com/questions/15568431/adding-dynamic-fields-to-nested-form-through-ajax

## Layouts

div_for: http://apidock.com/rails/ActionView/Helpers/RecordTagHelper/div_for

multiple layouts: http://stackoverflow.com/questions/15228228/multiple-layouts-in-ror

yield with default value: http://stackoverflow.com/questions/5922287/rails-3-yield-content-for-with-some-default-value

## HAML

haml basics: https://www.sitepoint.com/an-introduction-to-haml/

convert haml to erb: http://stackoverflow.com/questions/967262/is-there-a-good-haml-erb-html-converter

## Rack

http://stackoverflow.com/questions/2256569/what-is-rack-middleware

http://blog.gauravchande.com/what-is-rack-in-ruby-rails

https://blog.engineyard.com/2015/understanding-rack-apps-and-middleware

## Authentication and authorization

https://launchschool.com/blog/how-to-use-devise-in-rails-for-authentication

https://github.com/RolifyCommunity/rolify/wiki/Devise---CanCanCan---rolify-Tutorial

http://through-voidness.blogspot.com/2013/10/advanced-rails-4-authorization-with.html

http://blog.carbonfive.com/2013/10/21/migrating-to-pundit-from-cancan/

http://www.tonyamoyal.com/2010/07/28/rails-authentication-with-devise-and-cancan-customizing-devise-controllers/

http://www.tonyamoyal.com/2010/09/29/rails-authentication-with-devise-and-cancan-part-2-restful-resources-for-administrators/

http://stackoverflow.com/questions/11753600/cancan-how-to-allow-users-to-update-and-delete-only-their-own-objects

## Testing - RSpec

feature tests: https://www.madetech.com/blog/feature-testing-with-rspec

capybara basics: https://www.sitepoint.com/basics-capybara-improving-tests/

https://semaphoreci.com/community/tutorials/how-to-test-rails-models-with-rspec

https://robots.thoughtbot.com/how-we-test-rails-applications

http://betterspecs.org/

https://www.relishapp.com/rspec/rspec-rails/docs/generators

http://code.tutsplus.com/tutorials/ruby-for-newbies-testing-with-rspec--net-21297

http://blog.teamtreehouse.com/an-introduction-to-rspec

http://www.theodinproject.com/ruby-programming/introduction-to-rspec

https://www.youtube.com/watch?v=az4RYzd3Hmc

http://everydayrails.com/2012/07/31/rails-admin-panel-from-scratch.html

https://leanpub.com/everydayrailsrspec/read

## Various other things

redirect_to vs render: http://stackoverflow.com/questions/17236122/what-is-the-difference-between-link-to-redirect-to-and-render

nil vs empty vs blank: http://stackoverflow.com/questions/885414/a-concise-explanation-of-nil-v-empty-v-blank-in-ruby-on-rails

respond_with: http://wiki.summercode.com/cleaner_restful_controllers_with_respond_with

respond_with: http://www.justinweiss.com/articles/respond-to-without-all-the-pain/

simple search example: http://www.korenlc.com/creating-a-simple-search-in-rails-4/

search concern example: http://www.justinweiss.com/articles/search-and-filter-rails-models-without-bloating-your-controller/

formating dates: http://stackoverflow.com/questions/22255476/rails-formatting-date

seed photos: https://www.quora.com/Is-there-a-way-to-seed-fake-profile-photos-in-a-rails-application-along-the-lines-of-the-Faker-gem

what are turbolinks: https://thoughtbot.com/upcase/videos/turbolinks

using ckeditor wysiwyg with rails: http://wendybeth.github.io/blog/2014/10/29/how-to-use-ckeditor-with-rails-s-4/

rails problems with ckeditor: http://stackoverflow.com/questions/18752766/rails-4-with-ckeditor

generic code for static pages: http://blog.teamtreehouse.com/static-pages-ruby-rails

static pages - different approaches: http://stackoverflow.com/questions/4479233/static-pages-in-ruby-on-rails

simple form and bootstrap examples: http://simple-form-bootstrap.plataformatec.com.br/documentation

simple form custom inputs: http://arjanvandergaag.nl/blog/simpleform-custom-inputs.html

will_paginate gem explained: https://hackhands.com/pagination-rails-will_paginate-gem/

styling pagination: https://thewebfellas.com/blog/revisited-roll-your-own-pagination-links-with-will_paginate-and-rails-3


# Ruby

operator !!: http://stackoverflow.com/questions/524658/what-does-mean-in-ruby

operator &.: http://mitrev.net/ruby/2015/11/13/the-operator-in-ruby/

%w array: http://stackoverflow.com/questions/4455429/rails-using-w

difference between class and klass: http://stackoverflow.com/questions/4299289/what-is-the-difference-between-class-and-klass-in-ruby

metaprogramming: https://blog.codeship.com/metaprogramming-in-ruby/?utm_source=rubyweekly&utm_medium=email

send method: http://stackoverflow.com/questions/3337285/what-does-send-do-in-ruby

proc vs lambda: http://stackoverflow.com/questions/1740046/whats-the-difference-between-a-proc-and-a-lambda-in-ruby

class methods vs instance methods: http://www.railstips.org/blog/archives/2009/05/11/class-and-instance-methods-in-ruby/

blocks: http://rubylearning.com/satishtalim/ruby_blocks.html

string vs symbol: http://stackoverflow.com/questions/255078/whats-the-difference-between-a-string-and-a-symbol-in-ruby

when use symbols instead of strings: http://stackoverflow.com/questions/16621073/when-to-use-symbols-instead-of-strings-in-ruby

constantize: http://apidock.com/rails/String/constantize

## Ruby DSL

https://robots.thoughtbot.com/writing-a-domain-specific-language-in-ruby

http://engineering.gusto.com/benefits-of-writing-a-dsl/

http://rubylearning.com/blog/2010/11/30/how-do-i-build-dsls-with-yield-and-instance_eval/

https://www.leighhalliday.com/creating-ruby-dsl

https://quickleft.com/blog/drying-your-views-with-dsl-s/

http://stackoverflow.com/questions/4936146/tutorials-for-writing-dsl-in-ruby


# CSS

css modules in rails: https://medium.com/@fkadev/how-i-implemented-css-modules-to-ruby-on-rails-easily-abb324ce22d

# Javascript

javascript for rails: https://www.netguru.co/blog/java-script-ruby-on-rails-resources

about functions: https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/

## jquery

jquery basics: http://jqfundamentals.com/

## ajax

using ajax in rails: https://launchschool.com/blog/the-detailed-guide-on-how-ajax-works-with-ruby-on-rails

## js frameworks

from rails to ember.js: http://fromrailstoember.com/

react on rails: https://medium.com/@fkadev/r³-rails-react-redux-cef9a6e13e32

1 hour react course: https://www.udemy.com/react-basic-in-just-1-hour/

# GIT

git basics: http://rogerdudler.github.io/git-guide/

branching: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging

# Other Stuff

## Rails Apps Examples

https://vertalab.com/blog/ruby-on-rails-application-examples

## job interviews

interview questions with answers: http://www.skilledup.com/articles/ruby-on-rails-interview-questions-answers

rails entry level - what questions should you expect: know:https://www.quora.com/How-do-I-prepare-for-an-entry-level-Ruby-on-Rails-developer-interview-What-questions-should-I-expect

rails entry level - what should you know: https://www.quora.com/What-skills-must-a-Junior-Rails-Developer-need-know-in-order-to-be-successful-in-getting-an-entry-level-position

ruby quiz questions with answers: https://github.com/gregstallings/ruby-trivia

interview tips: https://www.interviewcake.com/

15 ruby interview questions: https://gist.github.com/ryansobol/5252653

becoming junior developer: https://ericbrooke.wordpress.com/2014/02/23/becoming-a-junior-rails-developer/

## Clean code and code quality

refactoring views: https://allenan.com/refactoring-rails-views/

where put code: http://codefol.io/posts/Where-Do-I-Put-My-Code

code optimization and cleanup: https://infinum.co/the-capsized-eight/articles/top-8-tools-for-ruby-on-rails-code-optimization-and-cleanup

fat models and skinny controllers: http://stackoverflow.com/questions/14044681/fat-models-and-skinny-controllers-sounds-like-creating-god-models

top 10 mistakes: https://www.toptal.com/ruby-on-rails/top-10-mistakes-that-rails-programmers-make

11 easy to fix mistakes: http://blog.sundaycoding.com/blog/2015/01/31/11-easy-to-fix-ruby-slash-ruby-on-rails-mistakes/

a lot about gems for quality: http://www.codelitt.com/blog/pragmatic-approach-building-ruby-rails-apps-quickly-quality-code/

## ZSH Shell

zsh for rails: https://viblo.asia/zenith.it/posts/aKYMNj6YM83E

## Interesting talks:

RailsConf 2014 - Keynote: Writing Software by David Heinemeier Hansson: https://www.youtube.com/watch?v=9LfmrkyP81M

RailsConf 2015 - Nothing is Something: https://www.youtube.com/watch?v=OMPfEXIlTVE
