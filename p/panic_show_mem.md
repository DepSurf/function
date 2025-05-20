# Function: <code>panic_show_mem</code>

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
void panic_show_mem(const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81bc38bc)
Location: init/initramfs.c:50
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:find_link
```
**Symbols:**

```
ffffffff81bc38bc-ffffffff81bc3925: panic_show_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void panic_show_mem(const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81c94933)
Location: init/initramfs.c:51
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_name
  - init/initramfs.c:find_link
```
**Symbols:**

```
ffffffff81c94933-ffffffff81c9499c: panic_show_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void panic_show_mem(const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81e43add)
Location: init/initramfs.c:62
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
```
**Symbols:**

```
ffffffff81e43add-ffffffff81e43b54: panic_show_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void panic_show_mem(const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81002470)
Location: init/initramfs.c:62
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
```
**Symbols:**

```
ffffffff81002470-ffffffff810024f7: panic_show_mem (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
