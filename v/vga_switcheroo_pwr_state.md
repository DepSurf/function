# Function: <code>vga_switcheroo_pwr_state</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d8a5)
Location: drivers/gpu/vga/vga_switcheroo.c:451
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff8172d4a0-ffffffff8172d4c6: vga_switcheroo_pwr_state.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81750045)
Location: drivers/gpu/vga/vga_switcheroo.c:456
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff8174fc40-ffffffff8174fc66: vga_switcheroo_pwr_state.part.5 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178bde8)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff8178ba20-ffffffff8178ba46: vga_switcheroo_pwr_state.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817afa08)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff817af640-ffffffff817af666: vga_switcheroo_pwr_state.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81875a74)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81884354)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81866bd4)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum vga_switcheroo_state vga_switcheroo_pwr_state(struct vga_switcheroo_client *client);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818f6147)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff818f6120-ffffffff818f616c: vga_switcheroo_pwr_state (STB_LOCAL)
ffffffff81d0f548-ffffffff81d0f55d: vga_switcheroo_pwr_state.cold (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81a46f81)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81bcdf41)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81c25b31)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81cd82b1)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81774538)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff81774170-ffffffff81774196: vga_switcheroo_pwr_state.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817542e8)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff81753f20-ffffffff81753f46: vga_switcheroo_pwr_state.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817a4888)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff817a44c0-ffffffff817a44e6: vga_switcheroo_pwr_state.part.0 (STB_LOCAL)
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
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817be708)
Location: drivers/gpu/vga/vga_switcheroo.c:455
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage1
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
**Symbols:**

```
ffffffff817be340-ffffffff817be366: vga_switcheroo_pwr_state.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
