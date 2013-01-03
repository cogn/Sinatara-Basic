Sinatara-Basic
==============

Sinatra is a free and open source software web application library and domain-specific language written in Ruby. It is an alternative to other Ruby web application frameworks such as Ruby on Rails, Merb, Nitro, Camping, and Rango. It is dependent on the Rack web server interface.




Step1 : gem install sinatra

Step2: Create the ruby file by require the sinatra gem

Step3: you can define the url as get,put, post,delete
Example
get '/' do
  'Minimal Sinatra Hello World!'
end

Step4:  
Render to the html views using the commands
erb :index in the action.