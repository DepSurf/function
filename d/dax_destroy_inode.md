# Function: <code>dax_destroy_inode</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163d180)
Location: drivers/dax/super.c:350
Inline: False
```
**Symbols:**

```
ffffffff8163d180-ffffffff8163d1ce: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5ef0)
Location: drivers/dax/super.c:379
Inline: False
```
**Symbols:**

```
ffffffff816a5ef0-ffffffff816a5f3e: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1a40)
Location: drivers/dax/super.c:405
Inline: False
```
**Symbols:**

```
ffffffff816e1a40-ffffffff816e1a8e: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81704e60)
Location: drivers/dax/super.c:404
Inline: False
```
**Symbols:**

```
ffffffff81704e60-ffffffff81704eae: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ee70)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffff8173ee70-ffffffff8173eea5: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763050)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffff81763050-ffffffff81763085: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822e10)
Location: drivers/dax/super.c:479
Inline: True
```
**Symbols:**

```
ffffffff81822e10-ffffffff81822e45: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831b20)
Location: drivers/dax/super.c:487
Inline: True
```
**Symbols:**

```
ffffffff81831b20-ffffffff81831b55: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814d50)
Location: drivers/dax/super.c:487
Inline: True
```
**Symbols:**

```
ffffffff81814d50-ffffffff81814d85: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f511)
Location: drivers/dax/super.c:474
Inline: True
```
**Symbols:**

```
ffffffff8189f4e0-ffffffff8189f528: dax_destroy_inode (STB_LOCAL)
ffffffff81d0b880-ffffffff81d0b894: dax_destroy_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff819e9363)
Location: drivers/dax/super.c:318
Inline: True
```
**Symbols:**

```
ffffffff819e9320-ffffffff819e937a: dax_destroy_inode (STB_LOCAL)
ffffffff81ed470a-ffffffff81ed471e: dax_destroy_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (0)
Location: drivers/dax/super.c:370
Inline: False
```
**Symbols:**

```
ffffffff81b659b0-ffffffff81b65a0a: dax_destroy_inode (STB_LOCAL)
ffffffff8209b5a0-ffffffff8209b5b4: dax_destroy_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb9065)
Location: drivers/dax/super.c:373
Inline: True
```
**Symbols:**

```
ffffffff81bb9020-ffffffff81bb907c: dax_destroy_inode (STB_LOCAL)
ffffffff8211c46f-ffffffff8211c483: dax_destroy_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d6c5)
Location: drivers/dax/super.c:374
Inline: True
```
**Symbols:**

```
ffffffff81c0d680-ffffffff81c0d6dc: dax_destroy_inode (STB_LOCAL)
ffffffff821fa2f6-ffffffff821fa30a: dax_destroy_inode.cold (STB_LOCAL)
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
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962ea0)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffff800010962ea0-ffff800010962ef4: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39eb4)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
c0a39eb4-c0a39f10: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19380)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
c000000000a19380-c000000000a193e8: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d03f2)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffe0005d03f2-ffffffe0005d0442: dax_destroy_inode (STB_LOCAL)
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
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717740)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffff81717740-ffffffff81717775: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efc70)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffff816efc70-ffffffff816efca5: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756510)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffff81756510-ffffffff81756545: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dax_destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771c00)
Location: drivers/dax/super.c:458
Inline: True
```
**Symbols:**

```
ffffffff81771c00-ffffffff81771c35: dax_destroy_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
