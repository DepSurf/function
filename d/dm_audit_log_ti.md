# Function: <code>dm_audit_log_ti</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void dm_audit_log_ti(int audit_type, const char *dm_msg_prefix, const char *op, struct dm_target *ti, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-audit.c (ffffffff81b6f860)
Location: drivers/md/dm-audit.c:36
Inline: False
```
**Symbols:**

```
ffffffff81b6f860-ffffffff81b6f9cc: dm_audit_log_ti (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_audit_log_ti(int audit_type, const char *dm_msg_prefix, const char *op, struct dm_target *ti, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-audit.c (ffffffff81d0be60)
Location: drivers/md/dm-audit.c:36
Inline: False
```
**Symbols:**

```
ffffffff81d0be60-ffffffff81d0bfcc: dm_audit_log_ti (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_audit_log_ti(int audit_type, const char *dm_msg_prefix, const char *op, struct dm_target *ti, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-audit.c (ffffffff81d74f90)
Location: drivers/md/dm-audit.c:36
Inline: False
```
**Symbols:**

```
ffffffff81d74f90-ffffffff81d75102: dm_audit_log_ti (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_audit_log_ti(int audit_type, const char *dm_msg_prefix, const char *op, struct dm_target *ti, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-audit.c (ffffffff81e2c0a0)
Location: drivers/md/dm-audit.c:36
Inline: False
```
**Symbols:**

```
ffffffff81e2c0a0-ffffffff81e2c212: dm_audit_log_ti (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
