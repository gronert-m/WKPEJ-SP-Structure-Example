### Run and Diagnose

Run the do-file. What filename does the failing command expect,
and how does it compare with your downloaded file?

<details>
<summary>Reveal hint</summary>

Compare the filename in the `use` command with the extracted
PBS filename, including its extension.

</details>

<details>
<summary>Reveal solution</summary>

PBS now provides a Stata file directly. Update the input command:

```stata
use "`path_in_stata'/LFS 2024-25.sav web.dta", clear
```

Despite containing `.sav` in its name, this file is a Stata
dataset: its extension is `.dta`.

</details>
