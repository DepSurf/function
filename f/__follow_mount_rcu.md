# Function: <code>__follow_mount_rcu</code>

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
In fs/namei.c (ffffffff8121775c)
Location: fs/namei.c:1254
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff8123e92e)
Location: fs/namei.c:1276
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812516fe)
Location: fs/namei.c:1273
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff8125d070)
Location: fs/namei.c:1285
Inline: True
Direct callers:
  - fs/namei.c:path_lookupat
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8125d070-ffffffff8125d14a: __follow_mount_rcu.isra.22 (STB_LOCAL)
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
In fs/namei.c (ffffffff8127f3e0)
Location: fs/namei.c:1283
Inline: True
Direct callers:
  - fs/namei.c:path_lookupat
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8127f3e0-ffffffff8127f4c7: __follow_mount_rcu.isra.26 (STB_LOCAL)
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
In fs/namei.c (ffffffff812a66a7)
Location: fs/namei.c:1270
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812a6250-ffffffff812a632f: __follow_mount_rcu.isra.35.part.36 (STB_LOCAL)
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
In fs/namei.c (ffffffff812bb777)
Location: fs/namei.c:1311
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812bb460-ffffffff812bb53f: __follow_mount_rcu.isra.35.part.36 (STB_LOCAL)
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
In fs/namei.c (ffffffff812d76b0)
Location: fs/namei.c:1309
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812d76b0-ffffffff812d778d: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812e9210)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812e9210-ffffffff812e92ed: __follow_mount_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __follow_mount_rcu(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321150)
Location: fs/namei.c:1312
Inline: False
Direct callers:
  - fs/namei.c:step_into
```
**Symbols:**

```
ffffffff81321150-ffffffff81321266: __follow_mount_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __follow_mount_rcu(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c6f0)
Location: fs/namei.c:1312
Inline: False
Direct callers:
  - fs/namei.c:step_into
```
**Symbols:**

```
ffffffff8132c6f0-ffffffff8132c801: __follow_mount_rcu (STB_LOCAL)
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
In fs/namei.c (ffffffff81333b4c)
Location: fs/namei.c:1397
Inline: True
Inline callers:
  - fs/namei.c:step_into
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
In fs/namei.c (ffffffff8138147b)
Location: fs/namei.c:1425
Inline: True
Inline callers:
  - fs/namei.c:step_into
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
In fs/namei.c (ffffffff81404e30)
Location: fs/namei.c:1469
Inline: True
Inline callers:
  - fs/namei.c:step_into
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
In fs/namei.c (ffffffff8148f2c8)
Location: fs/namei.c:1477
Inline: True
Inline callers:
  - fs/namei.c:step_into
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c4a86)
Location: fs/namei.c:1480
Inline: True
Inline callers:
  - fs/namei.c:step_into
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f7266)
Location: fs/namei.c:1483
Inline: True
Inline callers:
  - fs/namei.c:step_into
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
In fs/namei.c (ffff8000103925e0)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffff8000103925e0-ffff80001039270c: __follow_mount_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __follow_mount_rcu(struct nameidata *nd, struct path *path, struct inode **inode, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0578d48)
Location: fs/namei.c:1304
Inline: False
Direct callers:
  - fs/namei.c:path_lookupat
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
c0578d48-c0578e88: __follow_mount_rcu (STB_LOCAL)
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
In fs/namei.c (c00000000048b670)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
c00000000048b670-c00000000048b820: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffe0002617f4)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:path_lookupat
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffe0002617f4-ffffffe0002618f4: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812e17f0)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812e17f0-ffffffff812e18cd: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812d2430)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812d2430-ffffffff812d250d: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812df600)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812df600-ffffffff812df6dd: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812f0cb0)
Location: fs/namei.c:1304
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812f0cb0-ffffffff812f0d8d: __follow_mount_rcu.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
