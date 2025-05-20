# Function: <code>tomoyo_cred</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cebd8)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
```
In security/tomoyo/domain.c (ffffffff813d1766)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d678a)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d6e11)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
  - security/tomoyo/tomoyo.c:tomoyo_cred_alloc_blank
```
```
In security/tomoyo/util.c (ffffffff813d8138)
Location: security/tomoyo/common.h:1206
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f52f1)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
```
In security/tomoyo/domain.c (ffffffff813f7c76)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fccba)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fd343)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
  - security/tomoyo/tomoyo.c:tomoyo_cred_alloc_blank
```
```
In security/tomoyo/util.c (ffffffff813fe588)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81442a6f)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
```
```
In security/tomoyo/domain.c (ffffffff81445515)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff828ce8be)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff828cea78)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_file_open
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
  - security/tomoyo/tomoyo.c:tomoyo_cred_transfer
  - security/tomoyo/tomoyo.c:tomoyo_cred_alloc_blank
```
```
In security/tomoyo/util.c (ffffffff8144be9e)
Location: security/tomoyo/common.h:1208
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
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
