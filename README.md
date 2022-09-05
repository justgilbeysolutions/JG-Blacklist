# JG-Blacklist
Our baseline of blacklisted Appx apps that we want to remove initially

This can be kept updated by running the following:
Get-AppxPackage –AllUsers | Select Name, PackageFullName

Then entering the names of the apps you want removing pre-pended with #
e.g E046963F.LenovoCompanion
