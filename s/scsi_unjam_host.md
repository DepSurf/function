# Function: <code>scsi_unjam_host</code>

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
In drivers/scsi/scsi_error.c (ffffffff815ac805)
Location: drivers/scsi/scsi_error.c:2141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81604722)
Location: drivers/scsi/scsi_error.c:2141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81633e02)
Location: drivers/scsi/scsi_error.c:2141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81648a61)
Location: drivers/scsi/scsi_error.c:2071
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816b1b69)
Location: drivers/scsi/scsi_error.c:2096
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816ee1cd)
Location: drivers/scsi/scsi_error.c:2120
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81711dc5)
Location: drivers/scsi/scsi_error.c:2117
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8174d23a)
Location: drivers/scsi/scsi_error.c:2137
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff817713bc)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2142
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81833970-ffffffff81833b26: scsi_unjam_host (STB_LOCAL)
ffffffff81834150-ffffffff8183419f: scsi_unjam_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2155
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff818445a0-ffffffff81844756: scsi_unjam_host (STB_LOCAL)
ffffffff81c16818-ffffffff81c16867: scsi_unjam_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2177
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81827790-ffffffff81827946: scsi_unjam_host (STB_LOCAL)
ffffffff81c084f3-ffffffff81c08542: scsi_unjam_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2189
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff818b3150-ffffffff818b3306: scsi_unjam_host (STB_LOCAL)
ffffffff81d0c3ad-ffffffff81d0c3fc: scsi_unjam_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:2194
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff819fe300-ffffffff819fe4c6: scsi_unjam_host (STB_LOCAL)
ffffffff81ed52ec-ffffffff81ed5337: scsi_unjam_host.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7c7a0)
Location: drivers/scsi/scsi_error.c:2203
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81b7c7a0-ffffffff81b7c9a8: scsi_unjam_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bd0520)
Location: drivers/scsi/scsi_error.c:2249
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81bd0520-ffffffff81bd0728: scsi_unjam_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_unjam_host(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c25180)
Location: drivers/scsi/scsi_error.c:2255
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81c25180-ffffffff81c25388: scsi_unjam_host (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffff800010974920)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (c0a492bc)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (c000000000a2e8d0)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffe0005dd402)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81725aac)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816feedc)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8176487c)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8177fefc)
Location: drivers/scsi/scsi_error.c:2140
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
