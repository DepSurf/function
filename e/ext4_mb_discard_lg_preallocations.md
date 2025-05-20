# Function: <code>ext4_mb_discard_lg_preallocations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d0d50)
Location: fs/ext4/mballoc.c:4219
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff812d0d50-ffffffff812d107a: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81300900)
Location: fs/ext4/mballoc.c:4233
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81300900-ffffffff81300c12: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81316970)
Location: fs/ext4/mballoc.c:4240
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81316970-ffffffff81316c84: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130dd00)
Location: fs/ext4/mballoc.c:4298
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8130dd00-ffffffff8130e009: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813328e0)
Location: fs/ext4/mballoc.c:4298
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813328e0-ffffffff81332be9: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81360fc0)
Location: fs/ext4/mballoc.c:4268
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81360fc0-ffffffff813612bf: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81379270)
Location: fs/ext4/mballoc.c:4267
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81379270-ffffffff8137956f: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a2870)
Location: fs/ext4/mballoc.c:4268
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813a2870-ffffffff813a2b2f: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bb6d0)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813bb6d0-ffffffff813bb98f: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81406e70)
Location: fs/ext4/mballoc.c:4464
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
```
**Symbols:**

```
ffffffff81406e70-ffffffff814071e8: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141a0c0)
Location: fs/ext4/mballoc.c:4644
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_add_n_trim
```
**Symbols:**

```
ffffffff8141a0c0-ffffffff8141a435: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814206d0)
Location: fs/ext4/mballoc.c:5177
Inline: False
```
**Symbols:**

```
ffffffff814206d0-ffffffff81420a41: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81473a60)
Location: fs/ext4/mballoc.c:5233
Inline: False
```
**Symbols:**

```
ffffffff81473a60-ffffffff81473e3f: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f5220)
Location: fs/ext4/mballoc.c:5288
Inline: False
```
**Symbols:**

```
ffffffff814f5220-ffffffff814f56de: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8158f500)
Location: fs/ext4/mballoc.c:5259
Inline: False
```
**Symbols:**

```
ffffffff8158f500-ffffffff8158f9be: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c6180)
Location: fs/ext4/mballoc.c:5863
Inline: False
```
**Symbols:**

```
ffffffff815c6180-ffffffff815c662f: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff816008f0)
Location: fs/ext4/mballoc.c:5829
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff816008f0-ffffffff81600d99: ext4_mb_discard_lg_preallocations (STB_LOCAL)
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
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010492078)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffff800010492078-ffff80001049235c: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06533a4)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
c06533a4-c06536c8: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005ba290)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
c0000000005ba290-c0000000005ba7a4: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000316d0c)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffe000316d0c-ffffffe000317084: ext4_mb_discard_lg_preallocations (STB_LOCAL)
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
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b3cb0)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813b3cb0-ffffffff813b3f6f: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a4740)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813a4740-ffffffff813a49ff: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b1510)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813b1510-ffffffff813b17cf: ext4_mb_discard_lg_preallocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_mb_discard_lg_preallocations(struct super_block *sb, struct ext4_locality_group *lg, int order, int total_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c6040)
Location: fs/ext4/mballoc.c:4287
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff813c6040-ffffffff813c62f3: ext4_mb_discard_lg_preallocations (STB_LOCAL)
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
