[![StandWithPalestine](https://github.com/Safouene1/support-palestine-banner/blob/master/StandWithPalestine.svg)](https://github.com/Safouene1/support-palestine-banner)

# FetchIP-RB

FetchIP-RB is a Ruby script that retrieves the user's public, local IP address and displays detailed information such as the Internet Service Provider (ISP), country, region, city, and the country's flag as an emoji. The script also detects the primary language of the country associated with the IP address and displays the information in that language, with a fallback to English if the language is not supported. And now detects the computer's operating system and the version.

## Features

- Retrieves the user's local/public IP address. (IPv4 and IPv6)
- Displays detailed IP address information: ISP, country, region, city.
- Shows the country's flag as an emoji. (e.g. 🇫🇷 for France - Not supported on Windows)
- Detects the primary language of the country and displays information in that language. Support many languages.
- Fallback to English if the language is not supported or disconnected from the Internet.
- Detects the computer's operating system and the version.

## Dependencies

- Ruby (See [Installation](https://github.com/Lurmog/fetchip-rb/tree/help-with-installation/Installation.md))

## Usage

1. Download the `fetchip-rb.rb` script.
2. Run the script in your terminal using the command `ruby fetchip-rb.rb`.
3. You can also run the script to auto refresh IP details every # seconds using the command `ruby fetchip-rb.rb #` where # is the number of seconds to wait before refreshing. (e.g. `ruby fetchip-rb.rb 5` to refresh every 5 seconds)
4. Informations will appear in the terminal.

## License

This project is distributed under the GNU Affero General Public License version 3.0 (AGPL-3.0). This license requires that any modifications and larger works based on this project must also be released under the same license. Additionally, if you run a modified version of this software in a network server or provide access to it to others in any way, you must also make the source code available under this license. 

## Author

- Azx5G


## Acknowledgements

Special thanks to the following API providers for their essential services used in FetchIP-RB:

- **Httpbin** (https://httpbin.org): For the API to retrieve the public IP address.
- **Ifconfig.me** (https://ifconfig.me): For providing the public IPv6 address.
- **IP-API** (http://ip-api.com): For detailed IP information like ISP, country, region, and city.
- **Restcountries** (https://restcountries.com): For country data, including native names.
