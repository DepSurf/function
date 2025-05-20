# Function: <code>audit_log_uring</code>

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
void audit_log_uring(struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e87d0)
Location: kernel/auditsc.c:1643
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811e87d0-ffffffff811e89b9: audit_log_uring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_uring(struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122e840)
Location: kernel/auditsc.c:1621
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8122e840-ffffffff8122ea29: audit_log_uring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_uring(struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81244720)
Location: kernel/auditsc.c:1618
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81244720-ffffffff81244909: audit_log_uring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_uring(struct audit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125e580)
Location: kernel/auditsc.c:1613
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8125e580-ffffffff8125e769: audit_log_uring (STB_LOCAL)
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
