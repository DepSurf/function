# Function: <code>xlate_to_uni</code>

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
In fs/fat/namei_vfat.c (ffffffff812ff54d)
Location: fs/fat/namei_vfat.c:497
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff8133353d)
Location: fs/fat/namei_vfat.c:497
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff813492cd)
Location: fs/fat/namei_vfat.c:508
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff8135de7a)
Location: fs/fat/namei_vfat.c:508
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff81382b7a)
Location: fs/fat/namei_vfat.c:510
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff813b1550)
Location: fs/fat/namei_vfat.c:510
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff813cb334)
Location: fs/fat/namei_vfat.c:510
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
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
In fs/fat/namei_vfat.c (ffffffff813f6025)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (ffffffff8140fef5)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8145d040)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8145d040-ffffffff8145d233: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81478d10)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81478d10-ffffffff81478f03: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8147e780)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8147e780-ffffffff8147e973: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff814d5f30)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff814d5f30-ffffffff814d6123: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81563100)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81563100-ffffffff81563305: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81605c40)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81605c40-ffffffff81605e45: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8163db50)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8163db50-ffffffff8163dd6d: xlate_to_uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xlate_to_uni(const unsigned char *name, int len, unsigned char *outname, int *longlen, int *outlen, int escape, int utf8, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff816770c0)
Location: fs/fat/namei_vfat.c:511
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff816770c0-ffffffff816772dd: xlate_to_uni (STB_LOCAL)
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
In fs/fat/namei_vfat.c (ffff8000104f0cbc)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (c06ae674)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (c0000000006302e4)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (ffffffe000360b28)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (ffffffff814084d5)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (ffffffff813f8f55)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (ffffffff81405855)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
In fs/fat/namei_vfat.c (ffffffff8141b515)
Location: fs/fat/namei_vfat.c:511
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
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
