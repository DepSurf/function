# Function: <code>decode_suspend_state</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d8736)
Location: kernel/power/main.c:105
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d7736)
Location: kernel/power/main.c:105
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810df786)
Location: kernel/power/main.c:105
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e7f25)
Location: kernel/power/main.c:134
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f3535)
Location: kernel/power/main.c:134
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fb9f5)
Location: kernel/power/main.c:146
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81107e65)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
suspend_state_t decode_suspend_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112900)
Location: kernel/power/main.c:147
Inline: False
Direct callers:
  - kernel/power/main.c:mem_sleep_store
```
**Symbols:**

```
ffffffff81112900-ffffffff81112986: decode_suspend_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
suspend_state_t decode_suspend_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110f9d0)
Location: kernel/power/main.c:147
Inline: False
Direct callers:
  - kernel/power/main.c:mem_sleep_store
```
**Symbols:**

```
ffffffff8110f9d0-ffffffff8110fa56: decode_suspend_state (STB_LOCAL)
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
In kernel/power/main.c (ffffffff81110483)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
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
In kernel/power/main.c (ffffffff8112fe73)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81151513)
Location: kernel/power/main.c:150
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81180103)
Location: kernel/power/main.c:153
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81190ed3)
Location: kernel/power/main.c:194
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119f893)
Location: kernel/power/main.c:178
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016f13c)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b9cdc)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c6de4)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f1365)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe335)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811095f5)
Location: kernel/power/main.c:147
Inline: True
Inline callers:
  - kernel/power/main.c:mem_sleep_store
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
