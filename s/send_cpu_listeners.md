# Function: <code>send_cpu_listeners</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8113ed89)
Location: kernel/taskstats.c:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811473bc)
Location: kernel/taskstats.c:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8115125c)
Location: kernel/taskstats.c:122
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff811538d9)
Location: kernel/taskstats.c:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff811600d9)
Location: kernel/taskstats.c:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8116f012)
Location: kernel/taskstats.c:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8117cb12)
Location: kernel/taskstats.c:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff811899c3)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81195906)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void send_cpu_listeners(struct sk_buff *skb, struct listener_list *listeners);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a9e30)
Location: kernel/taskstats.c:113
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811a9e30-ffffffff811a9f85: send_cpu_listeners (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void send_cpu_listeners(struct sk_buff *skb, struct listener_list *listeners);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a7430)
Location: kernel/taskstats.c:109
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff811a7430-ffffffff811a7585: send_cpu_listeners (STB_LOCAL)
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
In kernel/taskstats.c (ffffffff811a8c9b)
Location: kernel/taskstats.c:109
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff811d27e7)
Location: kernel/taskstats.c:109
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81207085)
Location: kernel/taskstats.c:110
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8124f3f5)
Location: kernel/taskstats.c:110
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff812667a5)
Location: kernel/taskstats.c:110
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81280695)
Location: kernel/taskstats.c:110
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffff80001020db84)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (c044c570)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (c00000000028bc28)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffe00016ea98)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118df26)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81181036)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff8118bcf6)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
In kernel/taskstats.c (ffffffff81199673)
Location: kernel/taskstats.c:113
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
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
