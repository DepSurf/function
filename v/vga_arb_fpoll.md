# Function: <code>vga_arb_fpoll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8153f440)
Location: drivers/gpu/vga/vgaarb.c:1164
Inline: True
```
**Symbols:**

```
ffffffff8153f440-ffffffff8153f4c3: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8163fad0)
Location: drivers/gpu/vga/vgaarb.c:1164
Inline: False
```
**Symbols:**

```
ffffffff8163fad0-ffffffff8163fb29: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81671370)
Location: drivers/gpu/vga/vgaarb.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81671370-ffffffff816713c9: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff816859d0)
Location: drivers/gpu/vga/vgaarb.c:1269
Inline: False
```
**Symbols:**

```
ffffffff816859d0-ffffffff81685a29: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff816ef230)
Location: drivers/gpu/vga/vgaarb.c:1269
Inline: False
```
**Symbols:**

```
ffffffff816ef230-ffffffff816ef28c: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8172bcb0)
Location: drivers/gpu/vga/vgaarb.c:1269
Inline: False
```
**Symbols:**

```
ffffffff8172bcb0-ffffffff8172bd0c: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8174e450)
Location: drivers/gpu/vga/vgaarb.c:1269
Inline: False
```
**Symbols:**

```
ffffffff8174e450-ffffffff8174e4ac: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8178a1d0)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff8178a1d0-ffffffff8178a22f: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817addd0)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff817addd0-ffffffff817ade2f: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81874150)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff81874150-ffffffff818741af: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81882cf0)
Location: drivers/gpu/vga/vgaarb.c:1317
Inline: False
```
**Symbols:**

```
ffffffff81882cf0-ffffffff81882d4f: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81865540)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff81865540-ffffffff8186559f: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff818f48d0)
Location: drivers/gpu/vga/vgaarb.c:1297
Inline: False
```
**Symbols:**

```
ffffffff818f48d0-ffffffff818f492c: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff817f3ca0)
Location: drivers/pci/vgaarb.c:1410
Inline: False
```
**Symbols:**

```
ffffffff817f3ca0-ffffffff817f3d03: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff8191e320)
Location: drivers/pci/vgaarb.c:1410
Inline: False
```
**Symbols:**

```
ffffffff8191e320-ffffffff8191e383: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff819616d0)
Location: drivers/pci/vgaarb.c:1403
Inline: False
```
**Symbols:**

```
ffffffff819616d0-ffffffff81961733: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff819aaf10)
Location: drivers/pci/vgaarb.c:1403
Inline: False
```
**Symbols:**

```
ffffffff819aaf10-ffffffff819aaf73: vga_arb_fpoll (STB_LOCAL)
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
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffff8000109bf968)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffff8000109bf968-ffff8000109bf9e0: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c0a8d0dc)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
c0a8d0dc-c0a8d158: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c000000000a80c00)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
c000000000a80c00-c000000000a80cb4: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffe000612b50)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffe000612b50-ffffffe000612bbe: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817728f0)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff817728f0-ffffffff8177294f: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817526a0)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff817526a0-ffffffff817526ff: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817a2c50)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff817a2c50-ffffffff817a2caf: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t vga_arb_fpoll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817bcad0)
Location: drivers/gpu/vga/vgaarb.c:1318
Inline: False
```
**Symbols:**

```
ffffffff817bcad0-ffffffff817bcb2f: vga_arb_fpoll (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
