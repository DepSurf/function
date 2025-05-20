# Function: <code>_ldm_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff813cfdb0)
Location: block/partitions/ldm.c:53
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
**Symbols:**

```
ffffffff813cfdb0-ffffffff813cfe31: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814152e0)
Location: block/partitions/ldm.c:55
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
```
**Symbols:**

```
ffffffff814152e0-ffffffff81415361: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81430810)
Location: block/partitions/ldm.c:55
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
```
**Symbols:**

```
ffffffff81430810-ffffffff81430891: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8143d790)
Location: block/partitions/ldm.c:55
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_get_vstr
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
```
**Symbols:**

```
ffffffff8143d790-ffffffff8143d80f: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81469ae0)
Location: block/partitions/ldm.c:55
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_get_vstr
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
```
**Symbols:**

```
ffffffff81469ae0-ffffffff81469b5f: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8149f5b3)
Location: block/partitions/ldm.c:55
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_get_vstr
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
```
**Symbols:**

```
ffffffff8149f5b3-ffffffff8149f634: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814b9960)
Location: block/partitions/ldm.c:55
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_get_vstr
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
```
**Symbols:**

```
ffffffff814b9960-ffffffff814b99e1: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814e800c)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff814e800c-ffffffff814e808d: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff815013dc)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff815013dc-ffffffff8150145d: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81561d08)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
**Symbols:**

```
ffffffff81561d08-ffffffff81561d89: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81bf2c05)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_vmdb
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
**Symbols:**

```
ffffffff81bf2c05-ffffffff81bf2c86: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81be4c09)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
```
**Symbols:**

```
ffffffff81be4c09-ffffffff81be4c8a: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81cd8fb8)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_get_vnum
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff81cd8fb8-ffffffff81cd9039: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81e8caa1)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_get_vnum
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff81e8caa1-ffffffff81e8cb4c: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81757530)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_get_vnum
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
```
**Symbols:**

```
ffffffff81757530-ffffffff817575ce: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817948d0)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_get_vnum
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
```
**Symbols:**

```
ffffffff817948d0-ffffffff8179496e: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d8230)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_frag_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_get_vnum
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_create_data_partitions
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
  - block/partitions/ldm.c:ldm_parse_tocblock
```
**Symbols:**

```
ffffffff817d8230-ffffffff817d82ce: _ldm_printk (STB_LOCAL)
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
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffff800010603a64)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
  - block/partitions/ldm.c:ldm_parse_privhead
```
**Symbols:**

```
ffff800010603a64-ffff800010603b00: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c07aec5c)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
c07aec5c-c07aece4: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c00000000079f044)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_get_vstr
  - block/partitions/ldm.c:ldm_get_vnum
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
c00000000079f044-c00000000079f0f8: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffe00043ec26)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffe00043ec26-ffffffe00043ec8c: _ldm_printk (STB_LOCAL)
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
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814f99bc)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff814f99bc-ffffffff814f9a3d: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814e9ecc)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff814e9ecc-ffffffff814e9f4d: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814f5a4c)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff814f5a4c-ffffffff814f5acd: _ldm_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _ldm_printk(const char *level, const char *function, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8150eaac)
Location: block/partitions/ldm.c:41
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_relative
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff8150eaac-ffffffff8150eb2d: _ldm_printk (STB_LOCAL)
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
