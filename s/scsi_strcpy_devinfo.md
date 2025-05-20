# Function: <code>scsi_strcpy_devinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff815b65e0)
Location: drivers/scsi/scsi_devinfo.c:287
Inline: True
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff815b65e0-ffffffff815b6680: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff8160ecf0)
Location: drivers/scsi/scsi_devinfo.c:295
Inline: True
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8160ecf0-ffffffff8160ed90: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff8163e590)
Location: drivers/scsi/scsi_devinfo.c:293
Inline: True
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8163e590-ffffffff8163e630: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81652e10)
Location: drivers/scsi/scsi_devinfo.c:293
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81652e10-ffffffff81652eaf: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff816bc230)
Location: drivers/scsi/scsi_devinfo.c:294
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff816bc230-ffffffff816bc329: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:282
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff816f87a0-ffffffff816f8816: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff816f8ec0-ffffffff816f8edf: scsi_strcpy_devinfo.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:282
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8171b090-ffffffff8171b106: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff8171b7b0-ffffffff8171b7cf: scsi_strcpy_devinfo.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81756770-ffffffff817567e5: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81756de0-ffffffff81756dff: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8177aa10-ffffffff8177aa85: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff8177b080-ffffffff8177b09f: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:286
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8183db50-ffffffff8183dbc5: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff8183e1f0-ffffffff8183e20f: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:286
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8184e330-ffffffff8184e3a5: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81c16aa8-ffffffff81c16ac7: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:287
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff818317d0-ffffffff81831845: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81c08769-ffffffff81c08788: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:288
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff818bd820-ffffffff818bd895: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81d0c84e-ffffffff81d0c86d: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:288
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81a09a40-ffffffff81a09ac6: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81ed574a-ffffffff81ed5769: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81b88f70)
Location: drivers/scsi/scsi_devinfo.c:288
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81b88f70-ffffffff81b8902c: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81bdce50)
Location: drivers/scsi/scsi_devinfo.c:290
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81bdce50-ffffffff81bdcf0c: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81c31be0)
Location: drivers/scsi/scsi_devinfo.c:290
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81c31be0-ffffffff81c31c9c: scsi_strcpy_devinfo (STB_LOCAL)
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
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffff8000109804c0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffff8000109804c0-ffff800010980568: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (c0a52f3c)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
c0a52f3c-c0a52fd4: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (c000000000a3c110)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
c000000000a3c110-c000000000a3c1fc: scsi_strcpy_devinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffe0005e64da)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: True
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffe0005e64da-ffffffe0005e6570: scsi_strcpy_devinfo (STB_LOCAL)
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
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8172f100-ffffffff8172f175: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff8172f770-ffffffff8172f78f: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81708520-ffffffff81708595: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81708b90-ffffffff81708baf: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff8176ded0-ffffffff8176df45: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff8176e540-ffffffff8176e55f: scsi_strcpy_devinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void scsi_strcpy_devinfo(char *name, char *to, size_t to_length, char *from, int compatible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:285
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
**Symbols:**

```
ffffffff81789670-ffffffff817896e5: scsi_strcpy_devinfo (STB_LOCAL)
ffffffff81789ce0-ffffffff81789cff: scsi_strcpy_devinfo.cold (STB_LOCAL)
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
