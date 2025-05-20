# Function: <code>audit_log_multicast</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811885f0)
Location: kernel/audit.c:1560
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff811885f0-ffffffff811887e0: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185940)
Location: kernel/audit.c:1571
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff81185940-ffffffff81185b30: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186930)
Location: kernel/audit.c:1571
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff81186930-ffffffff81186b1d: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aed60)
Location: kernel/audit.c:1607
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff811aed60-ffffffff811aef4d: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e0fa0)
Location: kernel/audit.c:1587
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff811e0fa0-ffffffff811e11bc: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226df0)
Location: kernel/audit.c:1585
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff81226df0-ffffffff8122700c: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123d410)
Location: kernel/audit.c:1585
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff8123d410-ffffffff8123d62f: audit_log_multicast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_multicast(int group, const char *op, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81257340)
Location: kernel/audit.c:1603
Inline: False
Direct callers:
  - kernel/audit.c:audit_multicast_unbind
  - kernel/audit.c:audit_multicast_bind
```
**Symbols:**

```
ffffffff81257340-ffffffff81257557: audit_log_multicast (STB_LOCAL)
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
