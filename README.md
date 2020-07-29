# NS3 Cybersecurity Simulations
Common Cybersecurity Scenarios Simulations in NS3 and NetAnim [C++]

### Included
* **NS3 Suite** \[Supporting\]
    * NS3 Version = 3.31
    * NetAnim
    * Bake
* **Cybersecurity Scenarios** \[Main\]
* **Build Instructions** \[Supporting\]

## How To Build ?

### Build NS3
For building NS3 source, please check official documentation at [Official Installation for Linux and MacOS](https://www.nsnam.org/wiki/Installation#Linux)
### Build Scenatio / Simulation

To build a simulation from source (\*.cc)

##### Copy the source code from to "scratch" folder inside NS3 directory

##### Build with ./WAF

Use *waf* to build the scenario, replace with your prefered source (without extension *.cc*)

``
./waf --run <name_of_source_file>
``

for example the following command will build and run DDoSim.cc when put in scratch folder.

``
./waf --run DDoSim
``

*After build it can be found under **/build/scratch/** directory*

##### Simulate with NetAnim
After Execution, the program will produce respective XML file supported by NetAnim. Load the XML in NetAnim via interface and it will visualise the simulation.


## How to contribute ?
Just create the pull request with clear title of scenario, it should follow following basic rules :
* Follow general naming convention
* Try to make code clutter free
* Try to comment about main parts of code

## License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
