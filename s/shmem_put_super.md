# Function: <code>shmem_put_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a6f40)
Location: mm/shmem.c:2998
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff811a6f40-ffffffff811a6f9a: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bd430)
Location: mm/shmem.c:3648
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff811bd430-ffffffff811bd48a: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cdb00)
Location: mm/shmem.c:3565
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff811cdb00-ffffffff811cdb46: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d77c0)
Location: mm/shmem.c:3715
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff811d77c0-ffffffff811d781a: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ec640)
Location: mm/shmem.c:3764
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff811ec640-ffffffff811ec69a: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120dc40)
Location: mm/shmem.c:3480
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff8120dc40-ffffffff8120dc9a: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812207e0)
Location: mm/shmem.c:3466
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff812207e0-ffffffff8122083a: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122feb0)
Location: mm/shmem.c:3548
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff8122feb0-ffffffff8122ff0e: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123e140)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff8123e140-ffffffff8123e19e: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271bf2)
Location: mm/shmem.c:3591
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff8126b480-ffffffff8126b4de: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81278b41)
Location: mm/shmem.c:3699
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff81275e20-ffffffff81275e71: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127daf1)
Location: mm/shmem.c:3644
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff8127b230-ffffffff8127b281: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bbe44)
Location: mm/shmem.c:3617
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff812b90e0-ffffffff812b9131: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81317553)
Location: mm/shmem.c:3625
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff81314f80-ffffffff81314fd7: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138bf33)
Location: mm/shmem.c:3739
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff81388e40-ffffffff81388e97: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813be4a8)
Location: mm/shmem.c:3939
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff813bb070-ffffffff813bb0c7: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e5950)
Location: mm/shmem.c:4273
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff813e5950-ffffffff813e59c4: shmem_put_super (STB_LOCAL)
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
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102cfd10)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffff8000102cfd10-ffff8000102cfd6c: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04f9da8)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
c04f9da8-c04f9df8: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038db20)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
c00000000038db20-c00000000038dbc0: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ed44c)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffe0001ed44c-ffffffe0001ed4a2: shmem_put_super (STB_LOCAL)
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
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236790)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff81236790-ffffffff812367ee: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812297f0)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff812297f0-ffffffff8122984e: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81234530)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff81234530-ffffffff8123458e: shmem_put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shmem_put_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244450)
Location: mm/shmem.c:3628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
```
**Symbols:**

```
ffffffff81244450-ffffffff812444ae: shmem_put_super (STB_LOCAL)
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
