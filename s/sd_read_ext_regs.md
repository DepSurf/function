# Function: <code>sd_read_ext_regs</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sd_read_ext_regs(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1231
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81a434f0-ffffffff81a43892: sd_read_ext_regs (STB_LOCAL)
ffffffff81d2e28e-ffffffff81d2e372: sd_read_ext_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_read_ext_regs(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1238
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81bb11b0-ffffffff81bb12ef: sd_read_ext_regs (STB_LOCAL)
ffffffff81efa728-ffffffff81efa79c: sd_read_ext_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sd_read_ext_regs(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d550a0)
Location: drivers/mmc/core/sd.c:1240
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81d550a0-ffffffff81d55234: sd_read_ext_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sd_read_ext_regs(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbfa00)
Location: drivers/mmc/core/sd.c:1240
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81dbfa00-ffffffff81dbfb96: sd_read_ext_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sd_read_ext_regs(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e78160)
Location: drivers/mmc/core/sd.c:1240
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81e78160-ffffffff81e78325: sd_read_ext_regs (STB_LOCAL)
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
