# notadm<br>

2019-10-25: (coming soon) I want to do a bit more testing before adding the scripts.				<br>
														<br>
Notadm (not a display manager) are a few scripts that overwrite agetty's /etc/issue during system start.	<br>
Allows you to add whatever you'd want above your tty login prompt. 						<br>
see: https://www.reddit.com/r/archlinux/comments/dkqpd6/overwriting_etcissue_during_boot_with_script/		<br>

The Arch example uses archey3 + the info below it, dynamically creating /etc/issue during each boot.		<br>
																												<br>
![notadm](https://user-images.githubusercontent.com/36802396/67612285-34682780-f756-11e9-9b12-75b8f92018e4.png) <br>

The OpenSuse example was created with static edits to /etc/issue.						<br>

![suse](https://user-images.githubusercontent.com/36802396/115166350-906bed80-a067-11eb-8721-9126a1bf41da.png)	<br>


NEWS/UPDATE INFO:												<br>

UPDATE 2021-04-18:												<br>

Used this for a while now. Has proven relable with the test of time on my system.				<br>
Added the scripts I've been using to the repo.									<br>
Added the OpenSuse example as a statically edited /etc/issue.							<br>
