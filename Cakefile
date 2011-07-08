exec = require('child_process').exec

task 'build', ->
  exec 'coffee -o lib -c src/*.coffee', (err) ->
    console.log err if err

task 'test', -> require('./tests/test').run()

task 'benchmark', -> require('./benchmarks/benchmark').run()
