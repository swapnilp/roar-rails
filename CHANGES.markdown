h2. 0.0.10

* Empty resources now work properly in Rails 3.0 and 3.1.

h2. 0.0.9

* Changed `request.body.string` to `read` to make it work with Unicorn.

h2. 0.0.8

* Added `#represents` to configure consuming and rendering on controller class layer. This also calls `respond_to`.

h2. 0.0.7

* Introduce `:represent_with` and `:represent_items_with` for `#respond_with`. In turn, deprecate the old behaviour since it will change in 1.0.

h2. 0.0.6

* Make roar-rails rely on roar 0.10 and bigger.

h2. 0.0.4

* Added `#consume!` to infer representer name and parse the incoming document for a model.

h2. 0.0.3

* Works with Rails 3.0 now, too. Fixed the `mounted_helpers` import.
