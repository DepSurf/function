# Function: <code>do_mount_setattr</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8134f0f0)
Location: fs/namespace.c:3984
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
**Symbols:**

```
ffffffff8134f0f0-ffffffff8134f3a6: do_mount_setattr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4063
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
**Symbols:**

```
ffffffff8139d3c0-ffffffff8139d68f: do_mount_setattr.isra.0 (STB_LOCAL)
ffffffff81cc3f65-ffffffff81cc3f9c: do_mount_setattr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4131
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
**Symbols:**

```
ffffffff814202e0-ffffffff814205e2: do_mount_setattr.isra.0 (STB_LOCAL)
ffffffff81e7686d-ffffffff81e7689c: do_mount_setattr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4228
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
**Symbols:**

```
ffffffff814ac830-ffffffff814acb6b: do_mount_setattr.isra.0 (STB_LOCAL)
ffffffff82068c6e-ffffffff82068c9d: do_mount_setattr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4420
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
**Symbols:**

```
ffffffff814e1600-ffffffff814e185b: do_mount_setattr.isra.0 (STB_LOCAL)
ffffffff820e8590-ffffffff820e85bf: do_mount_setattr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4433
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
**Symbols:**

```
ffffffff815156d0-ffffffff81515925: do_mount_setattr.isra.0 (STB_LOCAL)
ffffffff821c52ea-ffffffff821c5319: do_mount_setattr.isra.0.cold (STB_LOCAL)
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
