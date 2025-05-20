# Function: <code>scsi_dev_info_list_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff815b6320)
Location: drivers/scsi/scsi_devinfo.c:406
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff815b6320-ffffffff815b64f0: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff8160ea30)
Location: drivers/scsi/scsi_devinfo.c:414
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8160ea30-ffffffff8160ebfc: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff8163e2d0)
Location: drivers/scsi/scsi_devinfo.c:412
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8163e2d0-ffffffff8163e49c: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81653220)
Location: drivers/scsi/scsi_devinfo.c:412
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81653220-ffffffff816533ec: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, int key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff816bc690)
Location: drivers/scsi/scsi_devinfo.c:404
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff816bc690-ffffffff816bc8a0: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:407
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff816f8bb0-ffffffff816f8dd6: scsi_dev_info_list_find (STB_LOCAL)
ffffffff816f8f22-ffffffff816f8f2e: scsi_dev_info_list_find.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:407
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8171b4a0-ffffffff8171b6c6: scsi_dev_info_list_find (STB_LOCAL)
ffffffff8171b812-ffffffff8171b81e: scsi_dev_info_list_find.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81756b30-ffffffff81756cfb: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81756e79-ffffffff81756e85: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8177add0-ffffffff8177af9b: scsi_dev_info_list_find (STB_LOCAL)
ffffffff8177b119-ffffffff8177b125: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:411
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8183df10-ffffffff8183e0db: scsi_dev_info_list_find (STB_LOCAL)
ffffffff8183e289-ffffffff8183e295: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:411
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8184e6f0-ffffffff8184e8bb: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81c16b41-ffffffff81c16b4d: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:412
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81831b90-ffffffff81831d5b: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81c08802-ffffffff81c0880e: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:413
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff818bdbe0-ffffffff818bddab: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81d0c8e7-ffffffff81d0c8f3: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:413
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81a09e50-ffffffff81a0a01d: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81ed57e3-ffffffff81ed57ef: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81b89430)
Location: drivers/scsi/scsi_devinfo.c:413
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81b89430-ffffffff81b89609: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81bdd320)
Location: drivers/scsi/scsi_devinfo.c:415
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81bdd320-ffffffff81bdd4f9: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffff81c320e0)
Location: drivers/scsi/scsi_devinfo.c:415
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_get_device_flags
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81c320e0-ffffffff81c322b9: scsi_dev_info_list_find (STB_LOCAL)
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
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffff8000109808a0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffff8000109808a0-ffff800010980aec: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (c0a5348c)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
c0a5348c-c0a536a8: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (c000000000a3c730)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
c000000000a3c730-c000000000a3ca70: scsi_dev_info_list_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (ffffffe0005e62f6)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffe0005e62f6-ffffffe0005e646c: scsi_dev_info_list_find (STB_LOCAL)
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
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8172f4c0-ffffffff8172f68b: scsi_dev_info_list_find (STB_LOCAL)
ffffffff8172f809-ffffffff8172f815: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff817088e0-ffffffff81708aab: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81708c29-ffffffff81708c35: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff8176e290-ffffffff8176e45b: scsi_dev_info_list_find (STB_LOCAL)
ffffffff8176e5d9-ffffffff8176e5e5: scsi_dev_info_list_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct scsi_dev_info_list *scsi_dev_info_list_find(const char *vendor, const char *model, enum scsi_devinfo_key key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_devinfo.c (0)
Location: drivers/scsi/scsi_devinfo.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_del_keyed
```
**Symbols:**

```
ffffffff81789a30-ffffffff81789bfb: scsi_dev_info_list_find (STB_LOCAL)
ffffffff81789d79-ffffffff81789d85: scsi_dev_info_list_find.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int key</code> ➡️ <code>enum scsi_devinfo_key key</code>
</li>
</ul>
</details>
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
