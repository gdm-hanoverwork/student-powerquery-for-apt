# student-powerquery-for-apt

## Description:
This quick PowerQuery allows you to pull the student's Apt (addressdetail.unit) out of the Demographics Page, by using the person / contacts backend.

https://support.powerschool.com/exchange/view.action?download.id=1215

## Installations:
1. Install using Plugin Management
2. Enable the plugin
3. Use the below PowerQuerry DAT codes under "Instructions"

## Instructions:
Use in a Export Template (Tested):
* *powerquery;query=com.github.gdm-hanoverwork.students.apt

I believe this should work in the following:

In a Report:
* ~(*powerquery;query=com.github.gdm-hanoverwork.students.apt)

In a Quick Export:
* ^{*powerquery;query=com.github.gdm-hanoverwork.students.apt}

I believe this should also work inside an AutoSend, though I haven't tested this as well.
