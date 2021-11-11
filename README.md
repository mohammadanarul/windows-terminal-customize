# good Looking  windows-terminal-customize

	step-1: Install-Module posh-git -Scope CurrentUser
	step-2: Install-Module oh-my-posh -Scope CurrentUser
	step-3: Install-Module -Name PSReadLine -Scope CurrentUser -Force -SkipPublisherCheck

	# check path

	step-4: echo $profile

	show path: C:\Users\codingwithdjango\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1

	# Visual code Editor Or Sublime Code Or Notepad

	step-5: subl $Profile OR code $Profile Or notepad $profile

		Import-Module posh-git
		Import-Module oh-my-posh
		Set-PoshPrompt -Theme hotstick.minimal


# Customize Theme hotstick.minimal

	Set-PoshPrompt -Theme hotstick.minimal

	Download link: C:\Users\codingwithdjango\Desktop\windows-terminal-customize\hotstick.minimal.omp.json

	file path: C:\Users\codingwithdjango\Documents\WindowsPowerShell\Modules\oh-my-posh\6.2.2\themes

	past new  file --> hotstick.minimal.omp.json


# Fix problem

	# Administration mode run your command line and past this code

	$ Set-ExecutionPolicy RemoteSigned






