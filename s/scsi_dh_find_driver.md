# Function: <code>scsi_dh_find_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff815b9a34)
Location: drivers/scsi/scsi_dh.c:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff816121ba)
Location: drivers/scsi/scsi_dh.c:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff816419ba)
Location: drivers/scsi/scsi_dh.c:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff8165628a)
Location: drivers/scsi/scsi_dh.c:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff816bf883)
Location: drivers/scsi/scsi_dh.c:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff816fbe95)
Location: drivers/scsi/scsi_dh.c:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff8171e875)
Location: drivers/scsi/scsi_dh.c:82
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81759f65)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff8177de75)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81840f40)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff81840f40-ffffffff81840fed: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81851460)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff81851460-ffffffff8185150d: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff818344f0)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff818344f0-ffffffff8183459d: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff818c04f0)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff818c04f0-ffffffff818c059d: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81a0cb60)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff81a0cb60-ffffffff81a0cc3a: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81b8c900)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff81b8c900-ffffffff81b8c9da: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81be0910)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff81be0910-ffffffff81be09ea: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *scsi_dh_find_driver(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81c35940)
Location: drivers/scsi/scsi_dh.c:71
Inline: False
Direct callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
**Symbols:**

```
ffffffff81c35940-ffffffff81c35a1a: scsi_dh_find_driver (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffff800010984328)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (c0a569a4)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (c000000000a411a0)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffe0005e91a0)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81732565)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff8170b985)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff81771335)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_dh.c (ffffffff8178cad5)
Location: drivers/scsi/scsi_dh.c:70
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
