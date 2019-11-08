
# worktimes

track work times of colleagues in different timezones

## dependencies

  - pendulum

## example

`t` means tomorrow, `lstart` and `lend` are their start and end times in your
local time. a `t` in the local columns means *your* tomorrow. a `t` in the
`start` and `end` columns is *their* tomorrow.

The row will be red if the current row is outside of work hours.

    name        time                     start     end       lstart    lend
    rusty       Sat 2019-11-09  05:56    09:00     17:00     14:30     22:30
    cdecker     Fri 2019-11-08  20:26    09:00t    17:00t    00:00t    08:00t
    lawrence    Fri 2019-11-08  20:26    09:00t    17:00t    00:00t    08:00t
    steven      Fri 2019-11-08  19:26    09:00t    17:00t    01:00t    09:00t
    alekos      Fri 2019-11-08  20:26    10:00t    18:00t    01:00t    09:00t
