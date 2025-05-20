# Function: <code>vme_check_window</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816ef8e0)
Location: drivers/vme/vme.c:180
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_slave_set
  - drivers/vme/vme.c:vme_master_set
```
**Symbols:**

```
ffffffff816ef8e0-ffffffff816ef9a3: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817548a0)
Location: drivers/vme/vme.c:180
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff817548a0-ffffffff81754960: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81780e60)
Location: drivers/vme/vme.c:183
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81780e60-ffffffff81780f20: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff8179fc00)
Location: drivers/vme/vme.c:206
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff8179fc00-ffffffff8179fcb9: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81816d50)
Location: drivers/vme/vme.c:206
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81816d50-ffffffff81816dea: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81860cd0)
Location: drivers/vme/vme.c:206
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81860cd0-ffffffff81860d6b: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81880480)
Location: drivers/vme/vme.c:206
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81880480-ffffffff8188051b: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff818cc579-ffffffff818cc58f: vme_check_window.cold (STB_LOCAL)
ffffffff818caa60-ffffffff818caaf9: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff818fe969-ffffffff818fe97f: vme_check_window.cold (STB_LOCAL)
ffffffff818fce50-ffffffff818fcee9: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff819d5705-ffffffff819d571b: vme_check_window.cold (STB_LOCAL)
ffffffff819d3c30-ffffffff819d3cc9: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:193
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81c2f6ef-ffffffff81c2f705: vme_check_window.cold (STB_LOCAL)
ffffffff819d37b0-ffffffff819d3849: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:193
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81c219b4-ffffffff81c219cb: vme_check_window.cold (STB_LOCAL)
ffffffff819b8a60-ffffffff819b8b05: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:193
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81d33717-ffffffff81d3372e: vme_check_window.cold (STB_LOCAL)
ffffffff81a67990-ffffffff81a67a35: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:193
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81effb94-ffffffff81effbaa: vme_check_window.cold (STB_LOCAL)
ffffffff81bd9090-ffffffff81bd9158: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6a5c0)
Location: drivers/staging/vme_user/vme.c:193
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_master_set
  - drivers/staging/vme_user/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81d6a5c0-ffffffff81d6a6c5: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd78a0)
Location: drivers/staging/vme_user/vme.c:193
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_master_set
  - drivers/staging/vme_user/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81dd78a0-ffffffff81dd79a5: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vme_check_window(struct vme_bridge *bridge, u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e8f9a0)
Location: drivers/staging/vme_user/vme.c:163
Inline: False
Direct callers:
  - drivers/staging/vme_user/vme.c:vme_master_set
  - drivers/staging/vme_user/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff81e8f9a0-ffffffff81e8fac3: vme_check_window (STB_GLOBAL)
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
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8c350)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffff800010b8c350-ffff800010b8c458: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c768e0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
c0c768e0-c0c76a2c: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c69e30)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
c000000000c69e30-c000000000c69fa8: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe0007327a6)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffe0007327a6-ffffffe000732866: vme_check_window (STB_GLOBAL)
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
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff8189fc99-ffffffff8189fcaf: vme_check_window.cold (STB_LOCAL)
ffffffff8189e180-ffffffff8189e219: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff8185b409-ffffffff8185b41f: vme_check_window.cold (STB_LOCAL)
ffffffff818598f0-ffffffff81859989: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff818ef389-ffffffff818ef39f: vme_check_window.cold (STB_LOCAL)
ffffffff818ed870-ffffffff818ed909: vme_check_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vme_check_window(u32 aspace, long long unsigned int vme_base, long long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:202
Inline: False
Direct callers:
  - drivers/vme/vme.c:vme_master_set
  - drivers/vme/vme.c:vme_slave_set
```
**Symbols:**

```
ffffffff8191040c-ffffffff81910422: vme_check_window.cold (STB_LOCAL)
ffffffff8190e8f0-ffffffff8190e989: vme_check_window (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vme_bridge *bridge</code>
</li>
<li>
<b>Param reordered. </b>
<code>aspace, vme_base, size</code> ➡️ <code>bridge, aspace, vme_base, size</code>
</li>
</ul>
</details>
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
