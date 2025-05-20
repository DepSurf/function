# Function: <code>devpts_fill_super</code>

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
In fs/devpts/inode.c (ffffffff8128df8c)
Location: fs/devpts/inode.c:377
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
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
In fs/devpts/inode.c (ffffffff812bb556)
Location: fs/devpts/inode.c:395
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812d0b30)
Location: fs/devpts/inode.c:389
Inline: True
```
**Symbols:**

```
ffffffff812d0b30-ffffffff812d0dd7: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812e2100)
Location: fs/devpts/inode.c:422
Inline: True
```
**Symbols:**

```
ffffffff812e2100-ffffffff812e23cc: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81306ae0)
Location: fs/devpts/inode.c:450
Inline: True
```
**Symbols:**

```
ffffffff81306ae0-ffffffff81306dac: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:450
Inline: True
```
**Symbols:**

```
ffffffff81334ae0-ffffffff81334d3f: devpts_fill_super (STB_LOCAL)
ffffffff81335274-ffffffff813352e9: devpts_fill_super.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff8134bedd)
Location: fs/devpts/inode.c:448
Inline: True
```
**Symbols:**

```
ffffffff8134be20-ffffffff8134c08a: devpts_fill_super (STB_LOCAL)
ffffffff8134c4f3-ffffffff8134c568: devpts_fill_super.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff813748af)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffff813747f0-ffffffff81374a52: devpts_fill_super (STB_LOCAL)
ffffffff81374f0b-ffffffff81374f80: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff8138cb2f)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffff8138ca70-ffffffff8138ccd2: devpts_fill_super (STB_LOCAL)
ffffffff8138d18b-ffffffff8138d200: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff813d7f60-ffffffff813d80e0: devpts_fill_super (STB_LOCAL)
ffffffff813d8658-ffffffff813d866e: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff813e9c00-ffffffff813e9d80: devpts_fill_super (STB_LOCAL)
ffffffff81bec1fc-ffffffff81bec212: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff813f0650-ffffffff813f08b2: devpts_fill_super (STB_LOCAL)
ffffffff81bde224-ffffffff81bde299: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff81442540-ffffffff814427a2: devpts_fill_super (STB_LOCAL)
ffffffff81cc87fb-ffffffff81cc8870: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff814be2c0-ffffffff814be516: devpts_fill_super (STB_LOCAL)
ffffffff81e7b546-ffffffff81e7b5af: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff815560a0)
Location: fs/devpts/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff815560a0-ffffffff8155635b: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8158de50)
Location: fs/devpts/inode.c:427
Inline: False
```
**Symbols:**

```
ffffffff8158de50-ffffffff8158e10b: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff815c6b90)
Location: fs/devpts/inode.c:426
Inline: False
```
**Symbols:**

```
ffffffff815c6b90-ffffffff815c6e35: devpts_fill_super (STB_LOCAL)
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
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffff80001045e630)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffff80001045e630-ffff80001045e8b0: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c061f078)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
c061f078-c061f360: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c00000000057a610)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
c00000000057a610-c00000000057a9ac: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffe0002ee2f6)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffe0002ee2f6-ffffffe0002ee572: devpts_fill_super (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff8138510f)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffff81385050-ffffffff813852b2: devpts_fill_super (STB_LOCAL)
ffffffff8138576b-ffffffff813857e0: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff81375b9f)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffff81375ae0-ffffffff81375d42: devpts_fill_super (STB_LOCAL)
ffffffff813761fb-ffffffff81376270: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff81382bdf)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffff81382b20-ffffffff81382d82: devpts_fill_super (STB_LOCAL)
ffffffff8138323b-ffffffff813832b0: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devpts_fill_super(struct super_block *s, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (ffffffff813966ff)
Location: fs/devpts/inode.c:445
Inline: True
```
**Symbols:**

```
ffffffff81396640-ffffffff813968a2: devpts_fill_super (STB_LOCAL)
ffffffff81396d5b-ffffffff81396dd0: devpts_fill_super.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
