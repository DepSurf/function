# Function: <code>get_disk_and_module</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814974d0)
Location: block/genhd.c:1463
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814974d0-ffffffff8149753e: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b13f0)
Location: block/genhd.c:1488
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814b13f0-ffffffff814b145e: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814df5b0)
Location: block/genhd.c:1509
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814df5b0-ffffffff814df61b: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f89e0)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814f89e0-ffffffff814f8a4b: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155a465)
Location: block/genhd.c:1731
Inline: True
Inline callers:
  - block/genhd.c:exact_lock
Direct callers:
  - block/genhd.c:get_gendisk
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff81559460-ffffffff815594ce: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f9e78)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffff8000105f9e78-ffff8000105f9ef0: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a50e0)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
c07a50e0-c07a5150: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000792d90)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
c000000000792d90-c000000000792e5c: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe0004365da)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffe0004365da-ffffffe000436646: get_disk_and_module (STB_GLOBAL)
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
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f0fc0)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814f0fc0-ffffffff814f102b: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1500)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814e1500-ffffffff814e156b: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ed050)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814ed050-ffffffff814ed0bb: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kobject *get_disk_and_module(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815060c0)
Location: block/genhd.c:1518
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff815060c0-ffffffff8150612b: get_disk_and_module (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
