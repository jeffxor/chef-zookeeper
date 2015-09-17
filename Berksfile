source 'https://supermarket.chef.io'

metadata

cookbook 'runit', github: 'hw-cookbooks/runit', tag: '1.6.0'

group :integration do
  cookbook 'zookeeper_tester', path: 'test/cookbooks/zookeeper_tester'
end
