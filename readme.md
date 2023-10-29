Good day! How a couple of tools made my life easier in computer clubs that have ccboot diskless.

Like on a weekend morning I was not allowed to rest peacefully with various computer clubs since I serve them. Everyone complained about terrible lags after logging into the shell. I noticed that drive C: is 100% loaded.

The fact is that the disk speed cannot bypass the bottleneck of a gaming computer in the form of a 1Gbit/s network card, which is no more than 100Mb/s. Nowadays, ssd produces 350 Mb/s. I'm not even talking about nvme.

Why is there such a picture? After all, just yesterday everything was fast and smart.

The problem turns out to be updating chrome or edge, and sometimes indexing for the search service starts, which starts loading the C: drive at 100%.

And let's not forget that after rebooting the gaming station, ccboot does not remember that before that it indexed the disks for 40 minutes).

What to do. Check every evening to see if anything has been updated.

I think no. So there will be no personal life, especially for someone like me. Since I will have to check 15 clubs every day. This was not at all part of my plans. The solution was found in the form of a program.

It contains 4 points that were interesting to me:

1. General - Options for optimization are outlined here. Which will be applied to the image.

2. StopUpdates - Here you can postpone auto-updates of both the system and drivers until 2099

3. An interesting thing that helps to automatically activate Windows 10/11 upon boot. If we take into account that the same image is loaded on different computers and that there would be no messages like this

4. The cool thing here is that this is not a KMS with a pirated software, but simply a utility that activates the keys when loaded. I took from here https://ygoo.ru/how-to-almost-legally-activate-windows-10-with-a-legal-key-from-the-official-microsoft-website, the key and activation server and entered here

4. The most interesting thing for me is why I even pay attention to it, this is, of course, the “Fix 100% disk” item, there is only one option that I allowed
5. If you look closely, when you click the checkmark at the top, a list appears in the field. You can enter something of your own there. This utility instantly kills processes. What works even before the login screen and after. This was my tablet to check for updates only once a month and sleep peacefully knowing that this utility does the entire disk unloading process for me.


In order to understand how it works.

It does not start in windows loaded under super clients or something like that.

It just downloads. Next, the disk image is mounted in CCBOOT
Then launch the node data and select the disk that should have appeared after mounting the image
После выставляем нужные настройки и жмем "Install Fix"

После закрываем программу и сохраняем примонтированный образ. Все настройка закончена . Можно грузиться игровые станции. Так все просто и быстро.

You can download this tool from github https://github.com/EpicGamesFixer/DisklessBootSpeedUp/releases/tag/v.1.0.2.0
