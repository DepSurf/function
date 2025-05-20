# Function: <code>cdrom_open_write</code>

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
In drivers/cdrom/cdrom.c (ffffffff81600c64)
Location: drivers/cdrom/cdrom.c:898
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8166096b)
Location: drivers/cdrom/cdrom.c:898
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8168e75b)
Location: drivers/cdrom/cdrom.c:898
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff816a365d)
Location: drivers/cdrom/cdrom.c:896
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8170e972)
Location: drivers/cdrom/cdrom.c:896
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8174db4d)
Location: drivers/cdrom/cdrom.c:896
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff81771d7d)
Location: drivers/cdrom/cdrom.c:896
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817b0141)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817e042b)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818af790)
Location: drivers/cdrom/cdrom.c:900
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff818af790-ffffffff818afa38: cdrom_open_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818be510)
Location: drivers/cdrom/cdrom.c:900
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff818be510-ffffffff818be7b8: cdrom_open_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:900
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff818a0fc0-ffffffff818a12a8: cdrom_open_write (STB_LOCAL)
ffffffff81c0c66b-ffffffff81c0c6ce: cdrom_open_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:900
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81935810-ffffffff81935b34: cdrom_open_write (STB_LOCAL)
ffffffff81d13256-ffffffff81d13291: cdrom_open_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:900
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81a8e4c0-ffffffff81a8e836: cdrom_open_write (STB_LOCAL)
ffffffff81ede281-ffffffff81ede2b7: cdrom_open_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:900
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81c0f980-ffffffff81c0fd0e: cdrom_open_write (STB_LOCAL)
ffffffff8209e595-ffffffff8209e5aa: cdrom_open_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:901
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81c75270-ffffffff81c755f0: cdrom_open_write (STB_LOCAL)
ffffffff8211f97a-ffffffff8211f98f: cdrom_open_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cdrom_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:901
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81d29c70-ffffffff81d29ff0: cdrom_open_write (STB_LOCAL)
ffffffff82201150-ffffffff82201165: cdrom_open_write.cold (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0cdac)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (c0ae4b28)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (c000000000ac48c0)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffe000634512)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8179880b)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8178a4db)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817d52ab)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817ef54b)
Location: drivers/cdrom/cdrom.c:897
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
