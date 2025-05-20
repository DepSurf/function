# Function: <code>free_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_pid_ns(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8111f5c0)
Location: kernel/pid_namespace.c:163
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
**Symbols:**

```
ffffffff8111f5c0-ffffffff8111f5d0: free_pid_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_pid_ns(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81127637)
Location: kernel/pid_namespace.c:163
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
**Symbols:**

```
ffffffff81127500-ffffffff81127510: free_pid_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_pid_ns(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81131207)
Location: kernel/pid_namespace.c:182
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
**Symbols:**

```
ffffffff81131080-ffffffff81131090: free_pid_ns (STB_LOCAL)
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
In kernel/pid_namespace.c (ffffffff811326dc)
Location: kernel/pid_namespace.c:185
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffff8113f6c5)
Location: kernel/pid_namespace.c:178
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff8114e15e)
Location: kernel/pid_namespace.c:159
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff8115acfe)
Location: kernel/pid_namespace.c:159
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff811673bc)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff8117327c)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff811851e0)
Location: kernel/pid_namespace.c:151
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffff8000101e7278)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (c0427750)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (c000000000257a20)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
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
In kernel/pid_namespace.c (ffffffe00015ca64)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff8116b89c)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff8115ea9c)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff8116966c)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
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
In kernel/pid_namespace.c (ffffffff81176d7c)
Location: kernel/pid_namespace.c:160
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
```
</details>
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
</ul>
