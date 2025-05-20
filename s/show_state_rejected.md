# Function: <code>show_state_rejected</code>

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
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff819a54f0)
Location: drivers/cpuidle/sysfs.c:259
Inline: False
```
**Symbols:**

```
ffffffff819a54f0-ffffffff819a5510: show_state_rejected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff8198a160)
Location: drivers/cpuidle/sysfs.c:259
Inline: False
```
**Symbols:**

```
ffffffff8198a160-ffffffff8198a180: show_state_rejected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff81a34ac0)
Location: drivers/cpuidle/sysfs.c:259
Inline: False
```
**Symbols:**

```
ffffffff81a34ac0-ffffffff81a34ae0: show_state_rejected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff81ba1380)
Location: drivers/cpuidle/sysfs.c:259
Inline: False
```
**Symbols:**

```
ffffffff81ba1380-ffffffff81ba13aa: show_state_rejected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff81d430f0)
Location: drivers/cpuidle/sysfs.c:259
Inline: False
```
**Symbols:**

```
ffffffff81d430f0-ffffffff81d4311a: show_state_rejected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff81dad310)
Location: drivers/cpuidle/sysfs.c:266
Inline: False
```
**Symbols:**

```
ffffffff81dad310-ffffffff81dad33a: show_state_rejected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t show_state_rejected(struct cpuidle_state *state, struct cpuidle_state_usage *state_usage, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/sysfs.c (ffffffff81e653b0)
Location: drivers/cpuidle/sysfs.c:266
Inline: False
```
**Symbols:**

```
ffffffff81e653b0-ffffffff81e653da: show_state_rejected (STB_LOCAL)
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
