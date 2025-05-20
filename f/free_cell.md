# Function: <code>free_cell</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_cell(struct hash_cell *hc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a81e0)
Location: drivers/md/dm-ioctl.c:194
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff816a81e0-ffffffff816a8210: free_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_cell(struct hash_cell *hc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81708680)
Location: drivers/md/dm-ioctl.c:194
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:__hash_remove
```
**Symbols:**

```
ffffffff81708680-ffffffff817086b0: free_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_cell(struct hash_cell *hc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173a550)
Location: drivers/md/dm-ioctl.c:194
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:__hash_remove
```
**Symbols:**

```
ffffffff8173a550-ffffffff8173a580: free_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817565d5)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:__hash_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c87e5)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:__hash_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818112b7)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:__hash_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8183d2b7)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8187ff6e)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818b1e2e)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff8198190e)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81985f2e)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81969784)
Location: drivers/md/dm-ioctl.c:232
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81a11bed)
Location: drivers/md/dm-ioctl.c:233
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81b7a3a1)
Location: drivers/md/dm-ioctl.c:234
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81d18771)
Location: drivers/md/dm-ioctl.c:234
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81d81ae1)
Location: drivers/md/dm-ioctl.c:249
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
In drivers/md/dm-ioctl.c (ffffffff81e39151)
Location: drivers/md/dm-ioctl.c:249
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b08c4c)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be7650)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bfa7cc)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f752a)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81857cae)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181f2be)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a72de)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818c351e)
Location: drivers/md/dm-ioctl.c:195
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_hash_insert
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
</ul>
