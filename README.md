# bezzera-bb005-digital-timer based on ESP8266:
Bezzera BB005 modification to setup your grinding Time via digital Timer based on ESP8266

## This Modifikation features:
- You can install this mod without any modification on the original Hardware
- Get 1 or 2 Cups in a difinded time grinded and be able to abort the grinding
- Define your time for each Cup via a Standalone WLAN in extra Servermode
- Demo: https://youtu.be/tWOO4BNrsw0

## This Hardware is needed to run this Software
- ESP8266 - I chose a NodeMCU v3
- OLED Display - I chose a 0.96" OLED Display I2C 128 x 32 Pixel I2C (SSD1306)
- USB Power Supply - I chose to run off a USB Power Adapter with a MicroUSB Cable
- Digital Relay - we choose a 1-Channel-Relay-Module, 5V, with Optocoupler, High and Low Level Trigger, for Arduino
- little help maybe: https://www.carto.net/andre.mw/photos/thematic/household/bezzera_macinino_bb005/

## circuit diagram
- see the file in sources: grinder-timer.png

## How to Setup the grinding Time (Servermode):
1. Press the Button and hold it while powering on the Grinder - Now it shows you some Informations in the Display
2. Via your MobilePhone, Notebook, etc. pp. you can conncet to the WLAN Gateway (Name: Grinder-Configuration) and then access a small Website via a Browser on your Device
3. Set the Time for 1 or 2 Cups (Type http://192.168.4.1 in your Browser) and follow the content of the site.

## Changelog
Feel free to optimize your own Branch of this Code, we will not Change this one.
Changed the Display to SSD1306


# Disclaimer
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
