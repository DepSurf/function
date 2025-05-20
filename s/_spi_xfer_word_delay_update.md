# Function: <code>_spi_xfer_word_delay_update</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81879e83)
Location: drivers/spi/spi.c:3392
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
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
In drivers/spi/spi.c (ffffffff81888813)
Location: drivers/spi/spi.c:3488
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
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
In drivers/spi/spi.c (ffffffff8186b497)
Location: drivers/spi/spi.c:3531
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
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
In drivers/spi/spi.c (ffffffff818fa5a0)
Location: drivers/spi/spi.c:3589
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
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
In drivers/spi/spi.c (ffffffff81a4becc)
Location: drivers/spi/spi.c:3588
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _spi_xfer_word_delay_update(struct spi_transfer *xfer, struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd63a0)
Location: drivers/spi/spi.c:3816
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_validate
```
**Symbols:**

```
ffffffff81bd63a0-ffffffff81bd6477: _spi_xfer_word_delay_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _spi_xfer_word_delay_update(struct spi_transfer *xfer, struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c28850)
Location: drivers/spi/spi.c:3871
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_validate
```
**Symbols:**

```
ffffffff81c28850-ffffffff81c288c3: _spi_xfer_word_delay_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _spi_xfer_word_delay_update(struct spi_transfer *xfer, struct spi_device *spi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdb220)
Location: drivers/spi/spi.c:4037
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_validate
```
**Symbols:**

```
ffffffff81cdb220-ffffffff81cdb293: _spi_xfer_word_delay_update (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
