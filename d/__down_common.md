# Function: <code>__down_common</code>

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
In kernel/locking/semaphore.c (ffffffff81822436)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down_killable
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
In kernel/locking/semaphore.c (ffffffff8189ca06)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff818d18f6)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81908a9e)
Location: kernel/locking/semaphore.c:205
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81992c5e)
Location: kernel/locking/semaphore.c:205
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff819ef16e)
Location: kernel/locking/semaphore.c:205
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81a2a4ae)
Location: kernel/locking/semaphore.c:205
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81a9ad40)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81ad2690)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (0)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81c43440)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
Direct callers:
  - kernel/locking/semaphore.c:__down_killable
```
**Symbols:**

```
ffffffff81c43440-ffffffff81c43556: __down_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81c35480)
Location: kernel/locking/semaphore.c:204
Inline: False
Direct callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
**Symbols:**

```
ffffffff81c35480-ffffffff81c355a8: __down_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81d53c80)
Location: kernel/locking/semaphore.c:208
Inline: False
Direct callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
**Symbols:**

```
ffffffff81d53c80-ffffffff81d53dc7: __down_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81f24cb0)
Location: kernel/locking/semaphore.c:240
Inline: False
Direct callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
**Symbols:**

```
ffffffff81f24cb0-ffffffff81f24ec0: __down_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff820d04b0)
Location: kernel/locking/semaphore.c:240
Inline: False
Direct callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
**Symbols:**

```
ffffffff820d04b0-ffffffff820d057b: __down_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff82154840)
Location: kernel/locking/semaphore.c:240
Inline: False
Direct callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
**Symbols:**

```
ffffffff82154840-ffffffff8215490b: __down_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __down_common(struct semaphore *sem, long int state, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff82237680)
Location: kernel/locking/semaphore.c:240
Inline: False
Direct callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
**Symbols:**

```
ffffffff82237680-ffffffff8223774b: __down_common (STB_LOCAL)
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
In kernel/locking/semaphore.c (ffff800010da48bc)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (c0e9ca90)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (c000000000ee6ec4)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffe0008c78ae)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81a71500)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81a2d7f0)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81add910)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
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
In kernel/locking/semaphore.c (ffffffff81ae9cf0)
Location: kernel/locking/semaphore.c:204
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
</details>
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
