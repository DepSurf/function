# Function: <code>vchan_complete</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vchan_complete(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706cd0)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffffffff81706cd0-ffffffff81706f35: vchan_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vchan_complete(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81782580)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffffffff81782580-ffffffff817827e5: vchan_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vchan_complete(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b8fe0)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffffffff818b8fe0-ffffffff818b9255: vchan_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vchan_complete(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a06690)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffffffff81a06690-ffffffff81a06905: vchan_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vchan_complete(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f520)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffffffff81a4f520-ffffffff81a4f795: vchan_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vchan_complete(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9b1c0)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffffffff81a9b1c0-ffffffff81a9b435: vchan_complete (STB_LOCAL)
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
void vchan_complete(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe698)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
ffff8000107fe698-ffff8000107fe8e0: vchan_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vchan_complete(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (c091f9a8)
Location: drivers/dma/virt-dma.c:83
Inline: False
```
**Symbols:**

```
c091f9a8-c091fbac: vchan_complete (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
