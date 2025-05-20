# Function: <code>erst_get_record_id_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff814b41e0)
Location: drivers/acpi/apei/erst.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff814b41e0-ffffffff814b452e: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81503b60)
Location: drivers/acpi/apei/erst.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81503b60-ffffffff81503e8c: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81527d50)
Location: drivers/acpi/apei/erst.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81527d50-ffffffff8152807c: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8153aca0)
Location: drivers/acpi/apei/erst.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff8153aca0-ffffffff8153afe2: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8159d800)
Location: drivers/acpi/apei/erst.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff8159d800-ffffffff8159db42: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff815d663d-ffffffff815d6658: erst_get_record_id_next.cold.17 (STB_LOCAL)
ffffffff815d5500-ffffffff815d5847: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff815efded-ffffffff815efe08: erst_get_record_id_next.cold.17 (STB_LOCAL)
ffffffff815eecb0-ffffffff815eeff7: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81621b65-ffffffff81621b80: erst_get_record_id_next.cold (STB_LOCAL)
ffffffff81620a50-ffffffff81620d5d: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81643645-ffffffff81643660: erst_get_record_id_next.cold (STB_LOCAL)
ffffffff81642530-ffffffff8164283d: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff816efc20)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff816efc20-ffffffff816efd0f: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8170d000)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff8170d000-ffffffff8170d0ef: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff816ee650)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff816ee650-ffffffff816ee73f: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81768730)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81768730-ffffffff8176881f: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8189cf60)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff8189cf60-ffffffff8189d05e: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff819e5c10)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff819e5c10-ffffffff819e5d0e: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a2e270)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81a2e270-ffffffff81a2e381: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a794e0)
Location: drivers/acpi/apei/erst.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81a794e0-ffffffff81a795f1: erst_get_record_id_next (STB_GLOBAL)
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
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffff8000107ad6a0)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffff8000107ad6a0-ffff8000107ada1c: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff815ffa25-ffffffff815ffa40: erst_get_record_id_next.cold (STB_LOCAL)
ffffffff815fe940-ffffffff815fec4d: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81637485-ffffffff816374a0: erst_get_record_id_next.cold (STB_LOCAL)
ffffffff81636370-ffffffff8163667d: erst_get_record_id_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int erst_get_record_id_next(int *pos, u64 *record_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:540
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
  - drivers/acpi/apei/erst.c:erst_reader
```
**Symbols:**

```
ffffffff81651795-ffffffff816517b0: erst_get_record_id_next.cold (STB_LOCAL)
ffffffff81650680-ffffffff8165098d: erst_get_record_id_next (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
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
