# Function: <code>__show_mem</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void __show_mem(unsigned int filter, nodemask_t *nodemask, int max_zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff8203cf10)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - init/initramfs.c:panic_show_mem
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff8203cf10-ffffffff8203d00f: __show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __show_mem(unsigned int filter, nodemask_t *nodemask, int max_zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/show_mem.c (ffffffff813deb80)
Location: mm/show_mem.c:403
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff813deb80-ffffffff813dec4a: __show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __show_mem(unsigned int filter, nodemask_t *nodemask, int max_zone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/show_mem.c (ffffffff81408a50)
Location: mm/show_mem.c:400
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81408a50-ffffffff81408b1a: __show_mem (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
