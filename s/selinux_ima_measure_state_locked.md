# Function: <code>selinux_ima_measure_state_locked</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void selinux_ima_measure_state_locked(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:73
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
  - security/selinux/ima.c:selinux_ima_measure_state
```
**Symbols:**

```
ffffffff81be3348-ffffffff81be337a: selinux_ima_measure_state_locked.cold (STB_LOCAL)
ffffffff814f5f30-ffffffff814f601e: selinux_ima_measure_state_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void selinux_ima_measure_state_locked(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:73
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
  - security/selinux/ima.c:selinux_ima_measure_state
```
**Symbols:**

```
ffffffff81cd5455-ffffffff81cd549c: selinux_ima_measure_state_locked.cold (STB_LOCAL)
ffffffff81550a90-ffffffff81550b7b: selinux_ima_measure_state_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void selinux_ima_measure_state_locked(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:73
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
  - security/selinux/ima.c:selinux_ima_measure_state
```
**Symbols:**

```
ffffffff81e8826f-ffffffff81e882b5: selinux_ima_measure_state_locked.cold (STB_LOCAL)
ffffffff815e9f50-ffffffff815ea054: selinux_ima_measure_state_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void selinux_ima_measure_state_locked(struct selinux_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:73
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
  - security/selinux/ima.c:selinux_ima_measure_state
```
**Symbols:**

```
ffffffff82073fbe-ffffffff82073fd2: selinux_ima_measure_state_locked.cold (STB_LOCAL)
ffffffff816998f0-ffffffff81699a26: selinux_ima_measure_state_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void selinux_ima_measure_state_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:70
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
  - security/selinux/ima.c:selinux_ima_measure_state
```
**Symbols:**

```
ffffffff820f3b54-ffffffff820f3b68: selinux_ima_measure_state_locked.cold (STB_LOCAL)
ffffffff816d20f0-ffffffff816d221c: selinux_ima_measure_state_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void selinux_ima_measure_state_locked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ima.c (0)
Location: security/selinux/ima.c:70
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
  - security/selinux/ima.c:selinux_ima_measure_state
```
**Symbols:**

```
ffffffff821d0cf1-ffffffff821d0d05: selinux_ima_measure_state_locked.cold (STB_LOCAL)
ffffffff8170e750-ffffffff8170e87c: selinux_ima_measure_state_locked (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
