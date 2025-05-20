# Function: <code>inode_lru_list_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227ac1)
Location: fs/inode.c:394
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812500e1)
Location: fs/inode.c:402
Inline: True
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
In fs/inode.c (ffffffff81263181)
Location: fs/inode.c:404
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fe90)
Location: fs/inode.c:402
Inline: False
```
**Symbols:**

```
ffffffff8126fe90-ffffffff8126fed1: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812927c0)
Location: fs/inode.c:402
Inline: False
```
**Symbols:**

```
ffffffff812927c0-ffffffff81292801: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b86c0)
Location: fs/inode.c:408
Inline: False
```
**Symbols:**

```
ffffffff812b86c0-ffffffff812b8701: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd810)
Location: fs/inode.c:408
Inline: False
```
**Symbols:**

```
ffffffff812cd810-ffffffff812cd851: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea5b0)
Location: fs/inode.c:421
Inline: False
```
**Symbols:**

```
ffffffff812ea5b0-ffffffff812ea5f1: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbfe0)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffffffff812fbfe0-ffffffff812fc021: inode_lru_list_add (STB_LOCAL)
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
In fs/inode.c (ffffffff81336865)
Location: fs/inode.c:426
Inline: True
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
In fs/inode.c (ffffffff813421c5)
Location: fs/inode.c:427
Inline: True
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
In fs/inode.c (ffffffff813485c5)
Location: fs/inode.c:427
Inline: True
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
In fs/inode.c (ffffffff81396295)
Location: fs/inode.c:431
Inline: True
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103acbe8)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffff8000103acbe8-ffff8000103acc64: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c9b0)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
c058c9b0-c058ca18: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6860)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
c0000000004a6860-c0000000004a6900: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270f44)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffffffe000270f44-ffffffe000270fb8: inode_lru_list_add (STB_LOCAL)
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
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f45c0)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffffffff812f45c0-ffffffff812f4601: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e51e0)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffffffff812e51e0-ffffffff812e5221: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f23d0)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffffffff812f23d0-ffffffff812f2411: inode_lru_list_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inode_lru_list_add(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813039a0)
Location: fs/inode.c:425
Inline: False
```
**Symbols:**

```
ffffffff813039a0-ffffffff813039e1: inode_lru_list_add (STB_LOCAL)
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
