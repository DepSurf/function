# Function: <code>__traceiter_signal_deliver</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2420)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810b2420-ffffffff810b2471: __traceiter_signal_deliver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3a60)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810b3a60-ffffffff810b3aaf: __traceiter_signal_deliver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c5c50)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810c5c50-ffffffff810c5c9f: __traceiter_signal_deliver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dd250)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810dd250-ffffffff810dd2ab: __traceiter_signal_deliver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fd590)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff810fd590-ffffffff810fd5eb: __traceiter_signal_deliver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811095e0)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff811095e0-ffffffff8110963b: __traceiter_signal_deliver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_signal_deliver(void *__data, int sig, struct kernel_siginfo *info, struct k_sigaction *ka);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112f80)
Location: include/trace/events/signal.h:96
Inline: False
```
**Symbols:**

```
ffffffff81112f80-ffffffff81112fdb: __traceiter_signal_deliver (STB_GLOBAL)
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
