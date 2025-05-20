# Function: <code>mount_setattr_prepare</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mount *mount_setattr_prepare(struct mount_kattr *kattr, struct mount *mnt, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cf00)
Location: fs/namespace.c:3891
Inline: False
```
**Symbols:**

```
ffffffff8134cf00-ffffffff8134d0fa: mount_setattr_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mount *mount_setattr_prepare(struct mount_kattr *kattr, struct mount *mnt, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3970
Inline: False
```
**Symbols:**

```
ffffffff8139ae90-ffffffff8139b0cf: mount_setattr_prepare (STB_LOCAL)
ffffffff81cc3f1f-ffffffff81cc3f34: mount_setattr_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mount_setattr_prepare(struct mount_kattr *kattr, struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4034
Inline: False
```
**Symbols:**

```
ffffffff8141ddf0-ffffffff8141e006: mount_setattr_prepare (STB_LOCAL)
ffffffff81e7683c-ffffffff81e76851: mount_setattr_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mount_setattr_prepare(struct mount_kattr *kattr, struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4140
Inline: False
```
**Symbols:**

```
ffffffff814aa170-ffffffff814aa33e: mount_setattr_prepare (STB_LOCAL)
ffffffff82068c05-ffffffff82068c1a: mount_setattr_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mount_setattr_prepare(struct mount_kattr *kattr, struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4332
Inline: False
```
**Symbols:**

```
ffffffff814df220-ffffffff814df3fb: mount_setattr_prepare (STB_LOCAL)
ffffffff820e8543-ffffffff820e8558: mount_setattr_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mount_setattr_prepare(struct mount_kattr *kattr, struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:4345
Inline: False
```
**Symbols:**

```
ffffffff81512010-ffffffff815121e0: mount_setattr_prepare (STB_LOCAL)
ffffffff821c529d-ffffffff821c52b2: mount_setattr_prepare.cold (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *err</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct mount *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
