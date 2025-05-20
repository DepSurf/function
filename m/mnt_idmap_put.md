# Function: <code>mnt_idmap_put</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814acd2a)
Location: fs/namespace.c:303
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:free_vfsmnt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mnt_idmap_put(struct mnt_idmap *idmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff81506b80)
Location: fs/mnt_idmapping.c:268
Inline: True
Direct callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81506b80-ffffffff81506c2a: mnt_idmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mnt_idmap_put(struct mnt_idmap *idmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff8153b9b0)
Location: fs/mnt_idmapping.c:313
Inline: True
Direct callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff8153b9b0-ffffffff8153ba28: mnt_idmap_put (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
