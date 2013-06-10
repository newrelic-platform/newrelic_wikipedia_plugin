## New Relic Wikipedia Plugin

### Instructions for running the Wikipedia agent

1. Go to <a href="https://github.com/newrelic-platform/newrelic_wikipedia_plugin/tags" target="_blank">the tags list</a> and find the latest archive.
1. Download and extract the source
1. Run `bundle install`
2. Copy `config/template_newrelic_plugin.yml` and rename file `config/newrelic_plugin.yml`
1. Replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
1. Execute `./newrelic_wikipedia_agent`
1. Go back to the Plugins list, and after a brief period you will see an entry for the Wikipedia plugin
