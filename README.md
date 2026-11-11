![A hand resting flat on a large closed leather stud book on a timber desk, its brass clasp at the fore edge and a red ribbon marker trailing over the desk edge, bridles on the wall and a stable yard window behind](intro-banner.png)



# codeintel-Inconsistent-Naming-Convention-Detector

![A registrar at his desk in a stable office with his hand on the closed leather stud book, a brass lamp lit, sealing wax and a measuring stick on the desk, and plain stall doors seen through the window behind](banner.png)

![An emblem of a closed leather stud book with a brass clasp and a red ribbon marker on a round timber ground, with a brass measuring stick laid below it](logo.png)

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
