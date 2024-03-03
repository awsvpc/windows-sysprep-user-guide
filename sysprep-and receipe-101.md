<pre>
  sysprep - Run this just before capturing your image. Sysprep doesnt capture the image, it "cleans" the operating system and takes it back to a pre-install phase.

I think you mean WSIM (Windows System Image Manager) which is part of the WAIK (Windows Automated Installation Kit). You use WSIM to create your answer file.

Use imagex to capture your sysprep'd install of Windows. Imagex captures to a .wim file. You can then use imagex to apply the image to a pc.

DISM (Deployment Image Servicing and Management) tool includes functionality for mounting and unmounting images (wim files) so you can service them. (i.e. add drivers, enable features) etc...

Perhaps some articles will help. Some of these are step by step so they may make things clearer as to which piece fits in the puzzle:

Windows Imaging Format - Wikipedia, the free encyclopedia

Understanding Windows Imaging - Windows 7 Tutorial:
http://sourcedaddy.com/windows-7/understanding-windows-imaging.html

Sysprep a Windows 7 Machine ? Start to Finish V2 - Blog.BrianLeeJackson.com:
http://blog.brianleejackson.com/sysprep-a-windows-7-machine-%E2%80%93-start-to-finish-v2

Deployment Image Servicing and Management (DISM) - WinPE 3.0 Boot Environment. Using WinPE 3.0 Boot environment to deploy and capture images... - The IT Bros: 
http://theitbros.com/deployment-image-servicing-and-management-dism-winpe-3-0

How To Image and Deploy Windows 7 a Complete Guide - Using sysprep and imagex: http://benosullivan.co.uk/windows/how-to-image-and-deploy-windows-7-a-complete-guide/
Sysprep a Windows 7 Machine ? Start to Finish - The IT Bros : http://theitbros.com/sysprep-a-windows-7-machine-%E2%80%93-start-to-finish

http://www.orbitone.com/en/blog/documents/Windows%207%20Deployment.pdf
  
</pre>
