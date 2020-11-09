---
pagetitle: Release Notes for M24SR Component Drivers
lang: en
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

::: {.card .fluid}
::: {.sectione .dark}
<center>
# <small>Release Notes for</small> <mark>M24SR Component Drivers</mark>
Copyright &copy; 2017 STMicroelectronics\
    
[![ST logo](../../../../_htmresc/st_logo.png)](https://www.st.com){.logo}
</center>
:::
:::

# License

Licensed by ST under BSD 3-Clause license (the \"License\"). You may
not use this package except in compliance with the License. You may
obtain a copy of the License at:

[https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the M24SR component drivers.

:::

::: {.col-sm-12 .col-lg-8}
# Update History

::: {.collapse}
<input type="checkbox" id="collapse-section22" checked aria-hidden="true">
<label for="collapse-section22" aria-hidden="true">V1.1.1 / 03-April-2019</label>
<div>			

## Main Changes

- Update release notes format
- Reformat the BSD 3-Clause license declaration in the files header (replace license terms by a web reference to OSI website where those terms lie)

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section20" aria-hidden="true">
<label for="collapse-section20" aria-hidden="true">V1.1.0 / 21-April-2017</label>
<div>			

## Main Changes

- Calls BSP IO functions (NFC_IO_xxx) as unique low layer interface.
- Made it fully independent by board and device (no external inclusion).
- Adapt #defines and m24sr.h accordingly API.
- Types renaming uc8 -> uint8_t and uc16 -> uint16_t.
- Pass I2C device address as param to all functions that use it.
- Remove goto instructions.
- Moved here some functions: M24SR_RFConfig(), M24SR_SetI2CSynchroMode(), M24SR_IsAnswerReady().
- Added M24SR_GPO_Callback().
- Added M24SR_GPO_Callback().
- Move lib_M24SR.c/h from driver to application.


</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section19" aria-hidden="true">
<label for="collapse-section19" aria-hidden="true">V1.0.0 / 20-October-2014</label>
<div>			

## Main Changes

- First official release by STM MMY division


</div>
:::

:::
:::

<footer class="sticky">
For complete documentation on <mark>STM32 Microcontrollers</mark> ,
visit: [http://www.st.com/STM32](http://www.st.com/STM32)
</footer>
