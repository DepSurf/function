# Function: <code>collect_domain_accesses</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry *dir, const layer_mask_t[14] * layer_masks_dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:715
Inline: False
Direct callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff816396f0-ffffffff81639ab5: collect_domain_accesses (STB_LOCAL)
ffffffff81e89acf-ffffffff81e89b55: collect_domain_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry *dir, const layer_mask_t[15] * layer_masks_dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:717
Inline: False
Direct callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff816f0da0-ffffffff816f1174: collect_domain_accesses (STB_LOCAL)
ffffffff82074f12-ffffffff82074f99: collect_domain_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry *dir, const layer_mask_t[15] * layer_masks_dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:717
Inline: False
Direct callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff8172b240-ffffffff8172b5ed: collect_domain_accesses (STB_LOCAL)
ffffffff820f4ae0-ffffffff820f4b63: collect_domain_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool collect_domain_accesses(const const struct landlock_ruleset * domain, const const struct dentry * mnt_root, struct dentry *dir, const layer_mask_t[15] * layer_masks_dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176da10)
Location: security/landlock/fs.c:633
Inline: False
Direct callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff8176da10-ffffffff8176db1c: collect_domain_accesses (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const layer_mask_t[14] * layer_masks_dom</code> ➡️ <code>const layer_mask_t[15] * layer_masks_dom</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
