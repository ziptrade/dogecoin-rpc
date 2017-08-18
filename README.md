# dogecoin-rpc
1.Build:

  A. locally:
  
    $ git clone https://github.com/onitsoft/renoscoin-docker.git
    $ mkdir dogecoin-rpc/wallet_data
    $ cp dogecoin-rpc/dogecoin.conf dogecoin-rpc/wallet_data
    $ docker build -t dogecoin-rpc dogecoin-rpc/
   
    
  B. Get from docker hub:
  
    $ docker pull onit/dogecoin-rpc:latest
    

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
