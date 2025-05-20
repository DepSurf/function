# Function: <code>__spi_split_transfer_maxsize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81644e55)
Location: drivers/spi/spi.c:2308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81675f55)
Location: drivers/spi/spi.c:2335
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff8168aa7f)
Location: drivers/spi/spi.c:2498
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff816f429f)
Location: drivers/spi/spi.c:2568
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81730d39)
Location: drivers/spi/spi.c:2618
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81752ff9)
Location: drivers/spi/spi.c:2684
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81790ad6)
Location: drivers/spi/spi.c:2888
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff817b46c6)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __spi_split_transfer_maxsize(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer **xferp, size_t maxsize, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81879b30)
Location: drivers/spi/spi.c:3099
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81879b30-ffffffff81879c98: __spi_split_transfer_maxsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __spi_split_transfer_maxsize(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer **xferp, size_t maxsize, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818884c0)
Location: drivers/spi/spi.c:3188
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff818884c0-ffffffff81888624: __spi_split_transfer_maxsize (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8186b166)
Location: drivers/spi/spi.c:3194
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff818fa306)
Location: drivers/spi/spi.c:3323
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81a4ad48)
Location: drivers/spi/spi.c:3319
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81bd1f15)
Location: drivers/spi/spi.c:3510
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __spi_split_transfer_maxsize(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer **xferp, size_t maxsize, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c297a0)
Location: drivers/spi/spi.c:3516
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxwords
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81c297a0-ffffffff81c29905: __spi_split_transfer_maxsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __spi_split_transfer_maxsize(struct spi_controller *ctlr, struct spi_message *msg, struct spi_transfer **xferp, size_t maxsize, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdbfe0)
Location: drivers/spi/spi.c:3687
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxwords
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81cdbfe0-ffffffff81cdc145: __spi_split_transfer_maxsize (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c48cc)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (c0ab1994)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (c000000000a892cc)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffe000616e26)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff817791a6)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff81758f56)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff817a9546)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
In drivers/spi/spi.c (ffffffff817c33d6)
Location: drivers/spi/spi.c:2892
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
