# Function: <code>usb_alloc_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8160fec0)
Location: drivers/usb/core/urb.c:64
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8160fec0-ffffffff8160ff15: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8166fa90)
Location: drivers/usb/core/urb.c:64
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8166fa90-ffffffff8166fae5: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169d770)
Location: drivers/usb/core/urb.c:69
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8169d770-ffffffff8169d7b5: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816b2b80)
Location: drivers/usb/core/urb.c:69
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff816b2b80-ffffffff816b2bb0: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171e250)
Location: drivers/usb/core/urb.c:69
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8171e250-ffffffff8171e280: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175d6f0)
Location: drivers/usb/core/urb.c:69
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8175d6f0-ffffffff8175d720: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81781d30)
Location: drivers/usb/core/urb.c:69
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff81781d30-ffffffff81781d60: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817bf9f0)
Location: drivers/usb/core/urb.c:69
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817bf9f0-ffffffff817bfa46: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f0370)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817f0370-ffffffff817f03c6: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818c0610)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff818c0610-ffffffff818c0699: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818cc530)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff818cc530-ffffffff818cc5a6: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818afa50)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff818afa50-ffffffff818afac5: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81944ba0)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81944ba0-ffffffff81944c15: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81a9c690)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81a9c690-ffffffff81a9c6ee: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c21610)
Location: drivers/usb/core/urb.c:71
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81c21610-ffffffff81c2166e: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81c88590)
Location: drivers/usb/core/urb.c:71
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81c88590-ffffffff81c885ec: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81d3cfe0)
Location: drivers/usb/core/urb.c:71
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff81d3cfe0-ffffffff81d3d03c: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffff800010a1ffb0)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffff800010a1ffb0-ffff800010a2002c: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c0af7124)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
c0af7124-c0af718c: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c000000000ada0f0)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
c000000000ada0f0-c000000000ada16c: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe0006439da)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffe0006439da-ffffffe000643a64: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a8750)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817a8750-ffffffff817a87a6: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179a160)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8179a160-ffffffff8179a1b6: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e51f0)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817e51f0-ffffffff817e5246: usb_alloc_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct urb *usb_alloc_urb(int iso_packets, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817ff450)
Location: drivers/usb/core/urb.c:70
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_bulk_msg
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817ff450-ffffffff817ff4a6: usb_alloc_urb (STB_GLOBAL)
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
