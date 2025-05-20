# Function: <code>hv_is_hibernation_supported</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102fa60)
Location: arch/x86/hyperv/hv_init.c:534
Inline: False
```
**Symbols:**

```
ffffffff8102fa60-ffffffff8102fa75: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030690)
Location: arch/x86/hyperv/hv_init.c:561
Inline: False
```
**Symbols:**

```
ffffffff81030690-ffffffff810306a5: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031170)
Location: arch/x86/hyperv/hv_init.c:606
Inline: False
```
**Symbols:**

```
ffffffff81031170-ffffffff81031191: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:219
Inline: False
```
**Symbols:**

```
ffffffff81d32e7a-ffffffff81d32e8e: hv_is_hibernation_supported.cold (STB_LOCAL)
ffffffff81a60f60-ffffffff81a60f97: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:232
Inline: False
```
**Symbols:**

```
ffffffff81eff2d3-ffffffff81eff2e7: hv_is_hibernation_supported.cold (STB_LOCAL)
ffffffff81bd1570-ffffffff81bd15b7: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:232
Inline: False
```
**Symbols:**

```
ffffffff820aa3d1-ffffffff820aa3e5: hv_is_hibernation_supported.cold (STB_LOCAL)
ffffffff81d7cfe0-ffffffff81d7d027: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:466
Inline: False
```
**Symbols:**

```
ffffffff8212b8d0-ffffffff8212b8e4: hv_is_hibernation_supported.cold (STB_LOCAL)
ffffffff81deb3d0-ffffffff81deb417: hv_is_hibernation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool hv_is_hibernation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:495
Inline: False
```
**Symbols:**

```
ffffffff8220d4f7-ffffffff8220d50b: hv_is_hibernation_supported.cold (STB_LOCAL)
ffffffff81ea1670-ffffffff81ea16b7: hv_is_hibernation_supported (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
