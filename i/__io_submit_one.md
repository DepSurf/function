# Function: <code>__io_submit_one</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813094b7)
Location: fs/aio.c:1789
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff8132b0c0)
Location: fs/aio.c:1778
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff8132b0c0-ffffffff8132b4e8: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff8133df10)
Location: fs/aio.c:1794
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff8133df10-ffffffff8133e338: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81377fc0)
Location: fs/aio.c:1801
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81377fc0-ffffffff813781a1: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81385cc0)
Location: fs/aio.c:1799
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81385cc0-ffffffff81385ea1: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff8138ce10)
Location: fs/aio.c:1796
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff8138ce10-ffffffff8138cff1: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff813da580)
Location: fs/aio.c:1914
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff813da580-ffffffff813da75b: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81464f60)
Location: fs/aio.c:1938
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81464f60-ffffffff81465139: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff814f4f90)
Location: fs/aio.c:1939
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff814f4f90-ffffffff814f5169: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff8152bd50)
Location: fs/aio.c:1931
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff8152bd50-ffffffff8152bf31: __io_submit_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81560c30)
Location: fs/aio.c:1974
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81560c30-ffffffff81560e11: __io_submit_one.isra.0 (STB_LOCAL)
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
In fs/aio.c (ffff8000103fd994)
Location: fs/aio.c:1794
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (c05cf080)
Location: fs/aio.c:1794
Inline: True
Direct callers:
  - fs/aio.c:__se_sys_io_submit
```
**Symbols:**

```
c05cf080-c05cf54c: __io_submit_one.constprop.0 (STB_LOCAL)
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
In fs/aio.c (c000000000506ba0)
Location: fs/aio.c:1794
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
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
In fs/aio.c (ffffffe0002ab2b0)
Location: fs/aio.c:1794
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff813364f0)
Location: fs/aio.c:1794
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff813364f0-ffffffff81336918: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81326e70)
Location: fs/aio.c:1794
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81326e70-ffffffff81327292: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81333fc0)
Location: fs/aio.c:1794
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81333fc0-ffffffff813343e8: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffff81344c40)
Location: fs/aio.c:1794
Inline: True
Direct callers:
  - fs/aio.c:io_submit_one
```
**Symbols:**

```
ffffffff81344c40-ffffffff81345078: __io_submit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
