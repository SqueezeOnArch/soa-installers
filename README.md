# Squeeze on Arch (SOA) Installers

Repository for install scripts and installer images for Squeeze on Arch

This repository is made available free of charge for
non-commercial private use. Any commercial usage is strictly
prohibited.

SQUEEZE ON ARCH IS PROVIDED "AS IS" AND ANY EXPRESS OR IMPLIED
WARRANTIES ARE DISCLAIMED. IN NO EVENT SHALL THE SOFTWARE PROVIDER BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN
IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Use of Squeeze on Arch is at your own risk.


## Instructions for installation

1) Download raw version of relavent installer image from appropriate url:

https://github.com/SqueezeOnArch/soa-installers/raw/master/soa-image-wand-dual.img.zip
https://github.com/SqueezeOnArch/soa-installers/raw/master/soa-image-wand-quad.img.zip
https://github.com/SqueezeOnArch/soa-installers/raw/master/soa-image-cubox-i.img.zip
https://github.com/SqueezeOnArch/soa-installers/raw/master/soa-image-cubietruck.img.zip
https://github.com/SqueezeOnArch/soa-installers/raw/master/soa-image-rpi.img.zip

2) Extract .img file from the zip file

3) Flash .img file to 4G or greater sdcard

Windows - use Win32DiskImager or alternative

Linux - use dd:
```
sudo dd if=<imagename.img> of=/dev/sd<X> bs=1K
sync
```

4) Boot device from the sdcard with a wired Ethernet connection supporting DHCP

5) Connect to the device with a web browser using the address allocted by your router (DHCP server)

6) Accept installer disclamer and watch installation progress
