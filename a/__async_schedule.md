# Function: <code>__async_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a3220)
Location: kernel/async.c:148
Inline: False
Direct callers:
  - kernel/async.c:async_schedule
  - kernel/async.c:async_schedule_domain
```
**Symbols:**

```
ffffffff810a3220-ffffffff810a339d: __async_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a6930)
Location: kernel/async.c:148
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_domain
  - kernel/async.c:async_schedule
```
**Symbols:**

```
ffffffff810a6930-ffffffff810a6ab5: __async_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ac590)
Location: kernel/async.c:148
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_domain
  - kernel/async.c:async_schedule
```
**Symbols:**

```
ffffffff810ac590-ffffffff810ac715: __async_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a9160)
Location: kernel/async.c:148
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_domain
  - kernel/async.c:async_schedule
```
**Symbols:**

```
ffffffff810a9160-ffffffff810a92e6: __async_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810af9f0)
Location: kernel/async.c:152
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_domain
  - kernel/async.c:async_schedule
```
**Symbols:**

```
ffffffff810af9f0-ffffffff810afb78: __async_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b6850)
Location: kernel/async.c:152
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_domain
  - kernel/async.c:async_schedule
```
**Symbols:**

```
ffffffff810b6850-ffffffff810b69d7: __async_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
async_cookie_t __async_schedule(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810bf8f0)
Location: kernel/async.c:152
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_domain
  - kernel/async.c:async_schedule
```
**Symbols:**

```
ffffffff810bf8f0-ffffffff810bfa77: __async_schedule (STB_LOCAL)
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
</ul>
