# Function: <code>aa_alloc_secid</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff813ea9d0)
Location: security/apparmor/secid.c:35
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff813ea9d0-ffffffff813eaa06: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81412300)
Location: security/apparmor/secid.c:35
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81412300-ffffffff81412336: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81444610)
Location: security/apparmor/secid.c:130
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81444610-ffffffff8144467c: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81461580)
Location: security/apparmor/secid.c:35
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81461580-ffffffff814615b6: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff8148e850)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff8148e850-ffffffff8148e889: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff814a8710)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff814a8710-ffffffff814a8749: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81505c50)
Location: security/apparmor/secid.c:127
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81505c50-ffffffff81505cbf: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81522da0)
Location: security/apparmor/secid.c:127
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81522da0-ffffffff81522e0f: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81528f90)
Location: security/apparmor/secid.c:127
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81528f90-ffffffff81528fff: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81587330)
Location: security/apparmor/secid.c:127
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81587330-ffffffff8158739f: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff816277e0)
Location: security/apparmor/secid.c:120
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff816277e0-ffffffff81627873: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff816db840)
Location: security/apparmor/secid.c:120
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff816db840-ffffffff816db8d3: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81714f10)
Location: security/apparmor/secid.c:119
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81714f10-ffffffff81714fa3: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_alloc_secid(struct aa_label *label, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff817539f0)
Location: security/apparmor/secid.c:153
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff817539f0-ffffffff81753a83: aa_alloc_secid (STB_GLOBAL)
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
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffff80001059ee98)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffff80001059ee98-ffff80001059ef28: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (c074fc04)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
c074fc04-c074fc50: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (c000000000718b20)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
c000000000718b20-c000000000718bd8: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffe0003ea27a)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffe0003ea27a-ffffffe0003ea2f6: aa_alloc_secid (STB_GLOBAL)
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
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff814a0cf0)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff814a0cf0-ffffffff814a0d29: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff81491710)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff81491710-ffffffff81491749: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff8149cd90)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff8149cd90-ffffffff8149cdc9: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 aa_alloc_secid();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/secid.c (ffffffff814b5330)
Location: security/apparmor/secid.c:30
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_alloc
```
**Symbols:**

```
ffffffff814b5330-ffffffff814b536b: aa_alloc_secid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_label *label</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct aa_label *label</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_label *label</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
