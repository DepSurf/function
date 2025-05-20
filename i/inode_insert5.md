# Function: <code>inode_insert5</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ba000)
Location: fs/inode.c:1026
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812ba000-ffffffff812ba16f: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cf210)
Location: fs/inode.c:1047
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812cf210-ffffffff812cf3b7: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ec140)
Location: fs/inode.c:1060
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812ec140-ffffffff812ec2e7: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fdc90)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812fdc90-ffffffff812fde37: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81337110)
Location: fs/inode.c:1072
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff81337110-ffffffff81337316: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342a50)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff81342a50-ffffffff81342c56: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348a20)
Location: fs/inode.c:1078
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff81348a20-ffffffff81348c1a: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1082
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff81cc3cf8-ffffffff81cc3d24: inode_insert5.cold (STB_LOCAL)
ffffffff813966b0-ffffffff813968c8: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1163
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff81e76573-ffffffff81e76597: inode_insert5.cold (STB_LOCAL)
ffffffff814186c0-ffffffff814188b6: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1161
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff82068ae2-ffffffff82068b06: inode_insert5.cold (STB_LOCAL)
ffffffff814a3fc0-ffffffff814a41ae: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1205
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff820e8420-ffffffff820e8444: inode_insert5.cold (STB_LOCAL)
ffffffff814d9140-ffffffff814d932e: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1153
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff821c515d-ffffffff821c5181: inode_insert5.cold (STB_LOCAL)
ffffffff8150b830-ffffffff8150ba19: inode_insert5 (STB_GLOBAL)
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
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ae3e8)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffff8000103ae3e8-ffff8000103ae634: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058ed7c)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
c058ed7c-c058ef40: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004aa7a0)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
c0000000004aa7a0-c0000000004aaa88: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000273252)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffe000273252-ffffffe000273458: inode_insert5 (STB_GLOBAL)
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
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6270)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812f6270-ffffffff812f6417: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6e90)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812e6e90-ffffffff812e7037: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4080)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff812f4080-ffffffff812f4227: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *inode_insert5(struct inode *inode, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305790)
Location: fs/inode.c:1071
Inline: False
Direct callers:
  - fs/inode.c:insert_inode_locked4
```
**Symbols:**

```
ffffffff81305790-ffffffff81305923: inode_insert5 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
