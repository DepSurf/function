# Function: <code>do_md_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81698b50)
Location: drivers/md/md.c:5597
Inline: False
Direct callers:
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81698b50-ffffffff81699122: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f9be0)
Location: drivers/md/md.c:5610
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff816f9be0-ffffffff816fa1a0: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8172b470)
Location: drivers/md/md.c:5662
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff8172b470-ffffffff8172ba32: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81743d50)
Location: drivers/md/md.c:5877
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81743d50-ffffffff817442d4: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b5f00)
Location: drivers/md/md.c:5928
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff817b5f00-ffffffff817b6484: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5994
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff817fbdb0-ffffffff817fc07d: do_md_stop (STB_LOCAL)
ffffffff81800bbf-ffffffff81800e8f: do_md_stop.cold.89 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5981
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81827ea0-ffffffff8182816a: do_md_stop (STB_LOCAL)
ffffffff8182cdc2-ffffffff8182d092: do_md_stop.cold.88 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6043
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff8186a360-ffffffff8186a627: do_md_stop (STB_LOCAL)
ffffffff8186f392-ffffffff8186f666: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff8189c100-ffffffff8189c3c7: do_md_stop (STB_LOCAL)
ffffffff818a1155-ffffffff818a1429: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6342
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff8196c280-ffffffff8196c567: do_md_stop (STB_LOCAL)
ffffffff81970f9f-ffffffff81971257: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6376
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81973120-ffffffff819733ee: do_md_stop (STB_LOCAL)
ffffffff81c2709c-ffffffff81c27354: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6333
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81957210-ffffffff819574de: do_md_stop (STB_LOCAL)
ffffffff81c1924d-ffffffff81c19505: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6346
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff819fc8f0-ffffffff819fcbbe: do_md_stop (STB_LOCAL)
ffffffff81d28876-ffffffff81d28b2e: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6339
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81b63fc0-ffffffff81b642e3: do_md_stop (STB_LOCAL)
ffffffff81ef48dc-ffffffff81ef4b0d: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfed20)
Location: drivers/md/md.c:6326
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81cfed20-ffffffff81cff2f0: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d66ce0)
Location: drivers/md/md.c:6328
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81d66ce0-ffffffff81d672c1: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1dd40)
Location: drivers/md/md.c:6450
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81e1dd40-ffffffff81e1e24c: do_md_stop (STB_LOCAL)
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
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af07f8)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_array
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffff800010af07f8-ffff800010af0c28: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd1b6c)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_array
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
c0bd1b6c-c0bd204c: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdc740)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
c000000000bdc740-c000000000bdcd28: do_md_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e4816)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffe0006e4816-ffffffe0006e4c14: do_md_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff81841f80-ffffffff81842247: do_md_stop (STB_LOCAL)
ffffffff81846fd5-ffffffff818472a9: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818095e0-ffffffff818098a7: do_md_stop (STB_LOCAL)
ffffffff8180e635-ffffffff8180e909: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818915b0-ffffffff81891877: do_md_stop (STB_LOCAL)
ffffffff81896605-ffffffff818968d9: do_md_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_md_stop(struct mddev *mddev, int mode, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6144
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
```
**Symbols:**

```
ffffffff818ad190-ffffffff818ad452: do_md_stop (STB_LOCAL)
ffffffff818b25e5-ffffffff818b28b9: do_md_stop.cold (STB_LOCAL)
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
