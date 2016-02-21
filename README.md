# react-on-rails-generator-results-automation

# Setup

Make sure the 3 repos are siblings before starting:

* react_on_rails
* react-on-rails-generator-results-automation
* react_on_rails-generator-results


For version 3.0.3:

```ruby
rake all[3.0.3]
```

# Future Plans
Update the script so that we create a fresh rails install for all branches instead of just the comparison branches, that way we won't get issues with the `fresh_rails_install` branch being stale.
