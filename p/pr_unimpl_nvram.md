# Function: <code>pr_unimpl_nvram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff814b41b0)
Location: drivers/acpi/apei/erst.c:756
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff814b41b0-ffffffff814b41d9: pr_unimpl_nvram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81503b30)
Location: drivers/acpi/apei/erst.c:754
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff81503b30-ffffffff81503b59: pr_unimpl_nvram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81527d20)
Location: drivers/acpi/apei/erst.c:754
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff81527d20-ffffffff81527d49: pr_unimpl_nvram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8153ac70)
Location: drivers/acpi/apei/erst.c:750
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff8153ac70-ffffffff8153ac99: pr_unimpl_nvram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8159d7d0)
Location: drivers/acpi/apei/erst.c:750
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff8159d7d0-ffffffff8159d7f9: pr_unimpl_nvram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:751
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff815d54e0-ffffffff815d54ff: pr_unimpl_nvram (STB_LOCAL)
ffffffff815d662c-ffffffff815d663d: pr_unimpl_nvram.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:751
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff815eec90-ffffffff815eecaf: pr_unimpl_nvram (STB_LOCAL)
ffffffff815efddc-ffffffff815efded: pr_unimpl_nvram.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:743
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff81620a30-ffffffff81620a4f: pr_unimpl_nvram (STB_LOCAL)
ffffffff81621b54-ffffffff81621b65: pr_unimpl_nvram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:743
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff81642510-ffffffff8164252f: pr_unimpl_nvram (STB_LOCAL)
ffffffff81643634-ffffffff81643645: pr_unimpl_nvram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff816f0363)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8170d743)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff816ee9da)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81768aba)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
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
In drivers/acpi/apei/erst.c (ffffffff8189d32a)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_read
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
In drivers/acpi/apei/erst.c (ffffffff819e60bc)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:__erst_read
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
In drivers/acpi/apei/erst.c (ffffffff81a2e73c)
Location: drivers/acpi/apei/erst.c:743
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:__erst_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a79a20)
Location: drivers/acpi/apei/erst.c:776
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:__erst_read
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
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffff8000107ad4a8)
Location: drivers/acpi/apei/erst.c:743
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffff8000107ad4a8-ffff8000107ad4e0: pr_unimpl_nvram (STB_LOCAL)
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
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:743
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff815fe920-ffffffff815fe93f: pr_unimpl_nvram (STB_LOCAL)
ffffffff815ffa14-ffffffff815ffa25: pr_unimpl_nvram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:743
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff81636350-ffffffff8163636f: pr_unimpl_nvram (STB_LOCAL)
ffffffff81637474-ffffffff81637485: pr_unimpl_nvram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pr_unimpl_nvram();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:743
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
```
**Symbols:**

```
ffffffff81650660-ffffffff8165067f: pr_unimpl_nvram (STB_LOCAL)
ffffffff81651784-ffffffff81651795: pr_unimpl_nvram.cold (STB_LOCAL)
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
