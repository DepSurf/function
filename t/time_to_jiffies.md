# Function: <code>time_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff81311b50)
Location: fs/fuse/dir.c:76
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_do_setattr
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81311b50-ffffffff81311ba3: time_to_jiffies.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff81349200)
Location: fs/fuse/dir.c:78
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81346040-ffffffff81346093: time_to_jiffies.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135e9f7)
Location: fs/fuse/dir.c:66
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8135bbd0-ffffffff8135bc33: time_to_jiffies.part.15 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff813734e3)
Location: fs/fuse/dir.c:66
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81370560-ffffffff813705c3: time_to_jiffies.part.16 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff813981f3)
Location: fs/fuse/dir.c:66
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81395260-ffffffff813952c3: time_to_jiffies.part.17 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff813c73ae)
Location: fs/fuse/dir.c:66
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff813c4480-ffffffff813c44e3: time_to_jiffies.part.19 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff813e0590)
Location: fs/fuse/dir.c:51
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff813ddc20-ffffffff813ddc83: time_to_jiffies.part.17 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff8140c1fe)
Location: fs/fuse/dir.c:51
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff814098d0-ffffffff81409933: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff81425dae)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff81423230-ffffffff81423293: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff81475319)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
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
In fs/fuse/dir.c (ffffffff8148ff43)
Location: fs/fuse/dir.c:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
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
In fs/fuse/dir.c (ffffffff8149597b)
Location: fs/fuse/dir.c:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
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
In fs/fuse/dir.c (ffffffff814ed415)
Location: fs/fuse/dir.c:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
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
In fs/fuse/dir.c (ffffffff8157c27d)
Location: fs/fuse/dir.c:89
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
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
In fs/fuse/dir.c (ffffffff81621c8d)
Location: fs/fuse/dir.c:95
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
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
In fs/fuse/dir.c (ffffffff8165a0e6)
Location: fs/fuse/dir.c:95
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/fuse/dir.c (ffff800010509604)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffff800010506660-ffff8000105066dc: time_to_jiffies.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (c06c3284)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:entry_attr_timeout
  - fs/fuse/dir.c:attr_timeout
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:entry_attr_timeout
  - fs/fuse/dir.c:attr_timeout
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
c06c2678-c06c2708: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (c00000000064f394)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
c00000000064b9d0-c00000000064ba68: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffe000375098)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffe0003728f6-ffffffe00037294e: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff8141e38e)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff8141b810-ffffffff8141b873: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff8140ee0e)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff8140c290-ffffffff8140c2f3: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff8141a52e)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff814179b0-ffffffff81417a13: time_to_jiffies.part.0 (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff8143128e)
Location: fs/fuse/dir.c:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_change_entry_timeout
```
**Symbols:**

```
ffffffff8142e7a0-ffffffff8142e803: time_to_jiffies.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
