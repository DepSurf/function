# Function: <code>mmc_prepare_busy_cmd</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host *host, struct mmc_command *cmd, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a40cc8)
Location: drivers/mmc/core/mmc_ops.c:528
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81a41950-ffffffff81a4198c: mmc_prepare_busy_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host *host, struct mmc_command *cmd, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81bae57f)
Location: drivers/mmc/core/mmc_ops.c:558
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81baefe0-ffffffff81baf025: mmc_prepare_busy_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host *host, struct mmc_command *cmd, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d51e00)
Location: drivers/mmc/core/mmc_ops.c:558
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81d52980-ffffffff81d529c5: mmc_prepare_busy_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host *host, struct mmc_command *cmd, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbc836)
Location: drivers/mmc/core/mmc_ops.c:558
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81dbba00-ffffffff81dbba45: mmc_prepare_busy_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host *host, struct mmc_command *cmd, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e74e06)
Location: drivers/mmc/core/mmc_ops.c:558
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81e73fd0-ffffffff81e74015: mmc_prepare_busy_cmd (STB_GLOBAL)
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
