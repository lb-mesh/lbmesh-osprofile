# LB Mesh OS

This package will provide basic operating system profile which can be used for many different purposes. 

Installation
------

	npm install lbmesh-os --save
	

	
Usage
------

	const server = require('lbmesh-os').profile()
	console.log (server);

	/** Output from Console.Log running on Mac OS **/
	
	{ cwd: '/Users/username/ostest',
  	  hostname: 'MacBook.local',
      release: '18.2.0',
      platform: 'darwin',
      homedir: '/Users/username',
      arch: 'x64',
      type: 'Darwin' 
    }

Works cross-platform.


License
------

MIT. Copyright &copy; [Jamil Spain](http://www.jamilspain.com)




	