# Function: <code>init_vqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff814c3b90)
Location: drivers/virtio/virtio_balloon.c:387
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
```
```
In drivers/char/virtio_console.c (ffffffff815160b0)
Location: drivers/char/virtio_console.c:1873
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/net/virtio_net.c (ffffffff815f3fd0)
Location: drivers/net/virtio_net.c:1634
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff814c3b90-ffffffff814c3cca: init_vqs (STB_LOCAL)
ffffffff815160b0-ffffffff815163bd: init_vqs (STB_LOCAL)
ffffffff815f3fd0-ffffffff815f4181: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81514030)
Location: drivers/virtio/virtio_balloon.c:404
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81568d10)
Location: drivers/char/virtio_console.c:1880
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/net/virtio_net.c (ffffffff81653bf0)
Location: drivers/net/virtio_net.c:1636
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff81514030-ffffffff81514148: init_vqs (STB_LOCAL)
ffffffff81568d10-ffffffff81568ff4: init_vqs (STB_LOCAL)
ffffffff81653bf0-ffffffff81653da5: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81540b00)
Location: drivers/virtio/virtio_balloon.c:404
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81595470)
Location: drivers/char/virtio_console.c:1889
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81540b00-ffffffff81540c24: init_vqs (STB_LOCAL)
ffffffff81595470-ffffffff81595751: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81554400)
Location: drivers/virtio/virtio_balloon.c:405
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff815a9520)
Location: drivers/char/virtio_console.c:1897
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81554400-ffffffff8155452a: init_vqs (STB_LOCAL)
ffffffff815a9520-ffffffff815a97f6: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815b7e80)
Location: drivers/virtio/virtio_balloon.c:418
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8160fe40)
Location: drivers/char/virtio_console.c:1894
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815b7e80-ffffffff815b7fb0: init_vqs (STB_LOCAL)
ffffffff8160fe40-ffffffff8161011c: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815f0440)
Location: drivers/virtio/virtio_balloon.c:428
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8164c520)
Location: drivers/char/virtio_console.c:1883
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff815f0440-ffffffff815f0570: init_vqs (STB_LOCAL)
ffffffff8164c520-ffffffff8164c7ac: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8160aa20)
Location: drivers/virtio/virtio_balloon.c:470
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff8166a2c0)
Location: drivers/char/virtio_console.c:1856
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8160aa20-ffffffff8160abf1: init_vqs (STB_LOCAL)
ffffffff8166a2c0-ffffffff8166a54c: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:461
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816a00b0)
Location: drivers/char/virtio_console.c:1844
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8163e820-ffffffff8163e9d1: init_vqs (STB_LOCAL)
ffffffff8163fa02-ffffffff8163fa30: init_vqs.cold (STB_LOCAL)
ffffffff816a00b0-ffffffff816a0343: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816c2e60)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81660d90-ffffffff81660f51: init_vqs (STB_LOCAL)
ffffffff81661fc2-ffffffff81661ff0: init_vqs.cold (STB_LOCAL)
ffffffff816c2e60-ffffffff816c30f3: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:503
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81776850)
Location: drivers/char/virtio_console.c:1843
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff817108d0-ffffffff81710af5: init_vqs (STB_LOCAL)
ffffffff817114d2-ffffffff81711500: init_vqs.cold (STB_LOCAL)
ffffffff81776850-ffffffff81776ae6: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:497
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81791580)
Location: drivers/char/virtio_console.c:1843
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8172d4b0-ffffffff8172d6d5: init_vqs (STB_LOCAL)
ffffffff81c049f4-ffffffff81c04a22: init_vqs.cold (STB_LOCAL)
ffffffff81791580-ffffffff81791816: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:497
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81773580)
Location: drivers/char/virtio_console.c:1840
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff817109c0-ffffffff81710be5: init_vqs (STB_LOCAL)
ffffffff81bf65b1-ffffffff81bf65dd: init_vqs.cold (STB_LOCAL)
ffffffff81773580-ffffffff81773814: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:497
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff817f93c0)
Location: drivers/char/virtio_console.c:1840
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8178d3b0-ffffffff8178d5d5: init_vqs (STB_LOCAL)
ffffffff81cf51eb-ffffffff81cf5217: init_vqs.cold (STB_LOCAL)
ffffffff817f93c0-ffffffff817f9654: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:497
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff819393f0)
Location: drivers/char/virtio_console.c:1841
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff818c54e0-ffffffff818c5780: init_vqs (STB_LOCAL)
ffffffff81ebd382-ffffffff81ebd3ae: init_vqs.cold (STB_LOCAL)
ffffffff819393f0-ffffffff8193969a: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a15de0)
Location: drivers/virtio/virtio_balloon.c:490
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81a99580)
Location: drivers/char/virtio_console.c:1837
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81a15de0-ffffffff81a160a1: init_vqs (STB_LOCAL)
ffffffff81a99580-ffffffff81a9982a: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ee90)
Location: drivers/virtio/virtio_balloon.c:490
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81ae4df0)
Location: drivers/char/virtio_console.c:1837
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/net/virtio_net.c (ffffffff81c543fc)
Location: drivers/net/virtio_net.c:3866
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff81a5ee90-ffffffff81a5f151: init_vqs (STB_LOCAL)
ffffffff81ae4df0-ffffffff81ae509a: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81ab15f0)
Location: drivers/virtio/virtio_balloon.c:529
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81b381c0)
Location: drivers/char/virtio_console.c:1805
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/net/virtio_net.c (ffffffff81d05dd6)
Location: drivers/net/virtio_net.c:4427
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff81ab15f0-ffffffff81ab18b1: init_vqs (STB_LOCAL)
ffffffff81b381c0-ffffffff81b3846a: init_vqs (STB_LOCAL)
ffffffff81d05d90-ffffffff81d05e80: init_vqs (STB_LOCAL)
ffffffff821fff40-ffffffff821fff6a: init_vqs.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffff800010829a08)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffff8000108b2c40)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffff800010829a08-ffff800010829bcc: init_vqs (STB_LOCAL)
ffff8000108b2c40-ffff8000108b2ea0: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0947c90)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (c09afe34)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
c0947c90-c0947ea0: init_vqs (STB_LOCAL)
c09afe34-c09b013c: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0000000008d7b60)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (c00000000094f7b0)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
c0000000008d7b60-c0000000008d7db0: init_vqs (STB_LOCAL)
c00000000094f7b0-c00000000094fac8: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffe000520768)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffe000566c66)
Location: drivers/char/virtio_console.c:1845
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffe000520768-ffffffe000520906: init_vqs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816888b0)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81626c00-ffffffff81626dc1: init_vqs (STB_LOCAL)
ffffffff81627e32-ffffffff81627e60: init_vqs.cold (STB_LOCAL)
ffffffff816888b0-ffffffff81688b43: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff81666360)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8161b280-ffffffff8161b441: init_vqs (STB_LOCAL)
ffffffff8161c4a2-ffffffff8161c4d0: init_vqs.cold (STB_LOCAL)
ffffffff81666360-ffffffff816665f3: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816b6b30)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff81654bd0-ffffffff81654d91: init_vqs (STB_LOCAL)
ffffffff81655e02-ffffffff81655e30: init_vqs.cold (STB_LOCAL)
ffffffff816b6b30-ffffffff816b6dc3: init_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int init_vqs(struct virtio_balloon *vb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:463
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/char/virtio_console.c (ffffffff816d1140)
Location: drivers/char/virtio_console.c:1845
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_probe
```
**Symbols:**

```
ffffffff8166f5a0-ffffffff8166f761: init_vqs (STB_LOCAL)
ffffffff8167040b-ffffffff81670439: init_vqs.cold (STB_LOCAL)
ffffffff816d1140-ffffffff816d13d3: init_vqs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
