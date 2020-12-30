# Log Searches extension for phpBB

Creates a log of searched enquiries.

[![Build Status](https://github.com/david63/logsearches/workflows/Tests/badge.svg)](https://github.com/phpbb-extensions/david63/logsearches)
[![License](https://poser.pugx.org/david63/logsearches/license)](https://packagist.org/packages/david63/logsearches)
[![Latest Stable Version](https://poser.pugx.org/david63/logsearches/v/stable)](https://packagist.org/packages/david63/logsearches)
[![Latest Unstable Version](https://poser.pugx.org/david63/logsearches/v/unstable)](https://packagist.org/packages/david63/logsearches)
[![Total Downloads](https://poser.pugx.org/david63/logsearches/downloads)](https://packagist.org/packages/david63/logsearches)
[![codecov](https://codecov.io/gh/david63/logsearches/branch/master/graph/badge.svg?token=D2500PgRex)](https://codecov.io/gh/david63/logsearches)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d95819d1093b409d8e9d85103c44f55b)](https://www.codacy.com/manual/david63/logsearches?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=david63/logsearches&amp;utm_campaign=Badge_Grade)

[![Compatible](https://img.shields.io/badge/compatible-phpBB:3.2.x-blue.svg)](https://shields.io/)
[![Compatible](https://img.shields.io/badge/compatible-phpBB:3.3.x-blue.svg)](https://shields.io/)

## Minimum Requirements
* phpBB 3.2.0
* PHP 5.4

## Install
1. [Download the latest release](https://github.com/david63/logsearches/archive/3.2.zip) and unzip it.
2. Unzip the downloaded release and copy it to the `ext` directory of your phpBB board.
3. Navigate in the ACP to `Customise -> Manage extensions`.
4. Look for `Log searches` under the Disabled Extensions list and click its `Enable` link.

## Usage
1. Navigate in the ACP to `Extensions -> Search Log -> Search log options`.
2. Apply the settings that you require.
3. The results will be found `Maintenance -> Forum logs -> Search log`.

## Uninstall
1. Navigate in the ACP to `Customise -> Manage extensions`.
2. Click the `Disable` link for `Log searches`.
3. To permanently uninstall, click `Delete Data`, then delete the logsearches folder from `phpBB/ext/david63/`.

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2019 - David Wood