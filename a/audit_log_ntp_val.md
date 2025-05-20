# Function: <code>audit_log_ntp_val</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116e7a0)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffff8116e7a0-ffffffff8116e7ec: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117a620)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffff8117a620-ffffffff8117a66c: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81191145)
Location: kernel/auditsc.c:2578
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e365)
Location: kernel/auditsc.c:2595
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f2e5)
Location: kernel/auditsc.c:2593
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b81c5)
Location: kernel/auditsc.c:2611
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101ef790)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffff8000101ef790-ffff8000101ef7fc: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042fbc4)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
c042fbc4-c042fc38: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000262390)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
c000000000262390-c0000000002623f8: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe0001634c2)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffe0001634c2-ffffffe00016351e: audit_log_ntp_val (STB_LOCAL)
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
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81172c40)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffff81172c40-ffffffff81172c8c: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81165de0)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffff81165de0-ffffffff81165e2c: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170a10)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffff81170a10-ffffffff81170a5c: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_ntp_val(const struct audit_ntp_data *ad, const char *op, enum audit_ntp_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117e220)
Location: kernel/auditsc.c:2526
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
```
**Symbols:**

```
ffffffff8117e220-ffffffff8117e26c: audit_log_ntp_val (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
