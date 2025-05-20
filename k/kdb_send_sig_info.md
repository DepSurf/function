# Function: <code>kdb_send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kdb_send_sig_info(struct task_struct *t, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810923a0)
Location: kernel/signal.c:3594
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff810923a0-ffffffff81092479: kdb_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kdb_send_sig_info(struct task_struct *t, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095500)
Location: kernel/signal.c:3603
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff81095500-ffffffff810955d9: kdb_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kdb_send_sig_info(struct task_struct *t, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a4f0)
Location: kernel/signal.c:3630
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff8109a4f0-ffffffff8109a5ca: kdb_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kdb_send_sig_info(struct task_struct *t, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097670)
Location: kernel/signal.c:3685
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff81097670-ffffffff8109774a: kdb_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kdb_send_sig_info(struct task_struct *t, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e360)
Location: kernel/signal.c:3693
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
```
**Symbols:**

```
ffffffff8109e360-ffffffff8109e43a: kdb_send_sig_info (STB_GLOBAL)
```
</details>
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
</ul>
