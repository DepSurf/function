# Function: <code>clear_pmd_presence</code>

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
In arch/x86/mm/kmmio.c (ffffffff81072fcd)
Location: arch/x86/mm/kmmio.c:115
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8107459b)
Location: arch/x86/mm/kmmio.c:126
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8107811b)
Location: arch/x86/mm/kmmio.c:126
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8107699f)
Location: arch/x86/mm/kmmio.c:126
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
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
In arch/x86/mm/kmmio.c (ffffffff8107cd3f)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8107fdc0)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff81086900)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8108a4dc)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8108b14c)
Location: arch/x86/mm/kmmio.c:127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_pmd_presence(pmd_t *pmd, bool clear, pmdval_t *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092440)
Location: arch/x86/mm/kmmio.c:127
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff81092440-ffffffff81092521: clear_pmd_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_pmd_presence(pmd_t *pmd, bool clear, pmdval_t *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81091ae0)
Location: arch/x86/mm/kmmio.c:127
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff81091ae0-ffffffff81091bc2: clear_pmd_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_pmd_presence(pmd_t *pmd, bool clear, pmdval_t *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092620)
Location: arch/x86/mm/kmmio.c:127
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff81092620-ffffffff81092701: clear_pmd_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_pmd_presence(pmd_t *pmd, bool clear, pmdval_t *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810a2340)
Location: arch/x86/mm/kmmio.c:127
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff810a2340-ffffffff810a2421: clear_pmd_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810b69b5)
Location: arch/x86/mm/kmmio.c:127
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d1c0f)
Location: arch/x86/mm/kmmio.c:133
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d50bf)
Location: arch/x86/mm/kmmio.c:133
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_pmd_presence(pmd_t *pmd, bool clear, pmdval_t *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810dd7c0)
Location: arch/x86/mm/kmmio.c:133
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
**Symbols:**

```
ffffffff810dd7c0-ffffffff810dd8b7: clear_pmd_presence (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a10c)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff81078c12)
Location: arch/x86/mm/kmmio.c:127
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
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
In arch/x86/mm/kmmio.c (ffffffff8108a0bc)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff8108c35c)
Location: arch/x86/mm/kmmio.c:127
Inline: True
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
</ul>
