# Function: <code>sync_file_merge</code>

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
In drivers/dma-buf/sync_file.c (ffffffff815fd68e)
Location: drivers/dma-buf/sync_file.c:147
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
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
In drivers/dma-buf/sync_file.c (ffffffff8162baf4)
Location: drivers/dma-buf/sync_file.c:202
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81640d10)
Location: drivers/dma-buf/sync_file.c:219
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81640d10-ffffffff81641068: sync_file_merge.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816a9bb0)
Location: drivers/dma-buf/sync_file.c:219
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816a9bb0-ffffffff816a9f0e: sync_file_merge.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816e60d0)
Location: drivers/dma-buf/sync_file.c:219
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816e60d0-ffffffff816e6419: sync_file_merge.constprop.5 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81709460)
Location: drivers/dma-buf/sync_file.c:219
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81709460-ffffffff817097a9: sync_file_merge.constprop.5 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81744c20)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81744c20-ffffffff81744f98: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81768dd0)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81768dd0-ffffffff81769145: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff8182ae30)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
```
**Symbols:**

```
ffffffff8182ae30-ffffffff8182b1e0: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff8183bae0)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
```
**Symbols:**

```
ffffffff8183bae0-ffffffff8183bf5c: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff8181ed00)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8181ed00-ffffffff8181f1bd: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (0)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff818a9390-ffffffff818a985d: sync_file_merge.constprop.0 (STB_LOCAL)
ffffffff81d0bcc8-ffffffff81d0bd0c: sync_file_merge.constprop.0.cold (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (0)
Location: drivers/dma-buf/sync_file.c:203
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff819f3320-ffffffff819f3bc6: sync_file_merge.constprop.0 (STB_LOCAL)
ffffffff81ed4b2f-ffffffff81ed4b6c: sync_file_merge.constprop.0.cold (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81b70f70)
Location: drivers/dma-buf/sync_file.c:159
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81b70f70-ffffffff81b7106e: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81bc47a0)
Location: drivers/dma-buf/sync_file.c:159
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81bc47a0-ffffffff81bc489e: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81c18f50)
Location: drivers/dma-buf/sync_file.c:159
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81c18f50-ffffffff81c1904e: sync_file_merge.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffff80001096a178)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffff80001096a178-ffff80001096a4c4: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (c0a401b0)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
c0a401b0-c0a4050c: sync_file_merge.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (c000000000a22a80)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
c000000000a22a80-c000000000a22ed4: sync_file_merge.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffe0005d5ac6)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffe0005d5ac6-ffffffe0005d5d22: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff8171d4c0)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8171d4c0-ffffffff8171d835: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff816f6920)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff816f6920-ffffffff816f6c95: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff8175c290)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff8175c290-ffffffff8175c605: sync_file_merge.constprop.0 (STB_LOCAL)
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
In drivers/dma-buf/sync_file.c (ffffffff81777930)
Location: drivers/dma-buf/sync_file.c:210
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
**Symbols:**

```
ffffffff81777930-ffffffff81777ca5: sync_file_merge.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
