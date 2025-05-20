# Function: <code>early_lookup_bdev</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_lookup_bdev(const char *name, dev_t *devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/early-lookup.c (ffffffff836fe120)
Location: block/early-lookup.c:244
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:find_resume_device
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff836fe120-ffffffff836fe313: early_lookup_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_lookup_bdev(const char *name, dev_t *devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/early-lookup.c (ffffffff83931800)
Location: block/early-lookup.c:244
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:find_resume_device
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff83931800-ffffffff839319f3: early_lookup_bdev (STB_GLOBAL)
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
