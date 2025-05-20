# Function: <code>ns_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ns_cmp(struct aa_ns *a, struct aa_ns *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81388dc0)
Location: security/apparmor/label.c:109
Inline: False
Direct callers:
  - security/apparmor/label.c:profile_cmp
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81388dc0-ffffffff81388eb9: ns_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ns_cmp(struct aa_ns *a, struct aa_ns *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c3960)
Location: security/apparmor/label.c:109
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
```
**Symbols:**

```
ffffffff813c3960-ffffffff813c3a5f: ns_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ns_cmp(struct aa_ns *a, struct aa_ns *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813daef0)
Location: security/apparmor/label.c:109
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
```
**Symbols:**

```
ffffffff813daef0-ffffffff813dafef: ns_cmp (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff813ed8d9)
Location: security/apparmor/label.c:111
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
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
In security/apparmor/label.c (ffffffff814152e9)
Location: security/apparmor/label.c:111
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
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
In security/apparmor/label.c (ffffffff81447710)
Location: security/apparmor/label.c:111
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
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
In security/apparmor/label.c (ffffffff81464640)
Location: security/apparmor/label.c:111
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
  - security/apparmor/label.c:profile_cmp
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
In security/apparmor/label.c (ffffffff81491cce)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814abbfe)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff8150acdc)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff81527b7c)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff8152d686)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff8158ba76)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff8162d072)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff816e1b52)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff8171b13e)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffffffff81759b8e)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:sort_cmp
  - security/apparmor/label.c:sort_cmp
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
In security/apparmor/label.c (ffff8000105a3040)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
  - security/apparmor/label.c:profile_cmp
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
In security/apparmor/label.c (c0753214)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
  - security/apparmor/label.c:profile_cmp
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
In security/apparmor/label.c (c00000000071e1a8)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffe0003ed574)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:profile_cmp
  - security/apparmor/label.c:profile_cmp
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int ns_cmp(struct aa_ns *a, struct aa_ns *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a41de)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
```
```
In drivers/nvme/host/core.c (ffffffff81741040)
Location: drivers/nvme/host/core.c:3416
Inline: False
```
**Symbols:**

```
ffffffff81741040-ffffffff8174105f: ns_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int ns_cmp(struct aa_ns *a, struct aa_ns *b);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81494bfe)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
```
```
In drivers/nvme/host/core.c (ffffffff81722cd0)
Location: drivers/nvme/host/core.c:3416
Inline: False
```
**Symbols:**

```
ffffffff81722cd0-ffffffff81722cef: ns_cmp (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff814a027e)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814b88fe)
Location: security/apparmor/label.c:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
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
<b>Flavor</b>
<ul>
</ul>
