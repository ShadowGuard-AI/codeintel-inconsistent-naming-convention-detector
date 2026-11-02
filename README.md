![The quay before the sale: dock boards and the nearest sea chest in the foreground, coiled rope and crates with unlit lanterns, further chests smaller and bluer, the bell post and warehouse wall, then open water under a low sun laying one bright road, with no lettering anywhere](intro-banner.png)



# codeintel-Inconsistent-Naming-Convention-Detector

![A row of unclaimed sea chests on dock boards at low light, the nearest domed and iron bound at full attention, the rest falling away in teal shadow toward a brass bell, and the painted auction board on the warehouse wall carrying the project name in foam white on tar black](banner.png)

![One domed sea chest with two iron bands, rope handles, a compass rose painted in foam white on its lid, and one lantern amber glint on the hasp, over the project name hand lettered in foam white on tar black, the heading plate](logo.png)

![The quay in three bands: water and low sun steady far off with gulls crossing at long intervals, lantern flames flickering and signal flags fluttering in the middle band, and the loose end of the coiled rope shifting a finger's width at the quay edge in the near band, while the chest, its painted rose, the coil, and the bell stay still](scene.svg)

Identifies inconsistencies in naming conventions (e.g., variable names, function names) across the codebase. Uses regular expressions or simple parsing to detect violations of established naming patterns. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

![Major separator: a full run of signal flags spelling nothing, fluttering in sequence across the page](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-inconsistent-naming-convention-detector`

> **Lot note, wrong seller named.** The clone line above names ShadowStrikeHQ rather than ShadowGuard-AI. It is kept as printed and flagged here, not quietly mended. The repository LICENSE file carries the MIT License, while the closing line of this README reads Copyright (c) ShadowStrikeHQ; both facts stand as printed.


![Major separator: a full run of signal flags spelling nothing, fluttering in sequence across the page](sep-heavy.svg)

## Usage
`./codeintel-inconsistent-naming-convention-detector [params]`

> **Lot note, placeholder usage.** The usage line above is a placeholder that the argument parser does not accept. The invocation the parser in main.py does accept is `python3 main.py FILENAME [--variable-pattern REGEX] [--function-pattern REGEX]`, where filename, the path to the Python file to analyse, is a required positional argument that appears in no parameter entry below.


![Major separator: a full run of signal flags spelling nothing, fluttering in sequence across the page](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `--variable-pattern`: Regex for variable naming convention. Default is snake_case.
- `--function-pattern`: Regex for function naming convention. Default is snake_case.

![Minor separator: a short centred run of signal flags spelling nothing, fluttering in sequence](sep-light.svg)

> **Lot note, the exit code is not a verdict.** The program prints a headed list of inconsistencies, or the sentence reporting that none were found, and exits 0 in both cases. The printed list is the whole result.


![Major separator: a full run of signal flags spelling nothing, fluttering in sequence across the page](sep-heavy.svg)

## License
Copyright (c) ShadowStrikeHQ

> **Lot note, wrong seller named.** The copyright line above names ShadowStrikeHQ rather than ShadowGuard-AI. It is kept as printed and flagged here. The repository LICENSE file carries the MIT License.
