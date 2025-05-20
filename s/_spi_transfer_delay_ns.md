# Function: <code>_spi_transfer_delay_ns</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178f1f0)
Location: drivers/spi/spi.c:1093
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8178f1f0-ffffffff8178f254: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b2db0)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817b2db0-ffffffff817b2e14: _spi_transfer_delay_ns (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8187c657)
Location: drivers/spi/spi.c:1121
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff8188a86a)
Location: drivers/spi/spi.c:1145
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff8186d216)
Location: drivers/spi/spi.c:1157
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff818fd2b1)
Location: drivers/spi/spi.c:1231
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff81a4e837)
Location: drivers/spi/spi.c:1274
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff81bd5ffe)
Location: drivers/spi/spi.c:1389
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff81c2d25c)
Location: drivers/spi/spi.c:1389
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
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
In drivers/spi/spi.c (ffffffff81cdfc5c)
Location: drivers/spi/spi.c:1462
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi.c:spi_delay_exec
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c3b00)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffff8000109c3b00-ffff8000109c3b98: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab0598)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
c0ab0598-c0ab062c: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a86e60)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
c000000000a86e60-c000000000a86f24: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000617238)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffe000617238-ffffffe0006172c0: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81777890)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81777890-ffffffff817778f4: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81757640)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81757640-ffffffff817576a4: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a7c30)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817a7c30-ffffffff817a7c94: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void _spi_transfer_delay_ns(u32 ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c1ab0)
Location: drivers/spi/spi.c:1094
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817c1ab0-ffffffff817c1b14: _spi_transfer_delay_ns (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
