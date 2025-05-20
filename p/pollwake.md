# Function: <code>pollwake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pollwake(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81220df0)
Location: fs/select.c:208
Inline: True
```
**Symbols:**

```
ffffffff81220df0-ffffffff81220e79: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pollwake(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81248a80)
Location: fs/select.c:208
Inline: True
```
**Symbols:**

```
ffffffff81248a80-ffffffff81248b09: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pollwake(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125bab0)
Location: fs/select.c:209
Inline: True
```
**Symbols:**

```
ffffffff8125bab0-ffffffff8125bb39: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81268a10)
Location: fs/select.c:209
Inline: True
```
**Symbols:**

```
ffffffff81268a10-ffffffff81268a99: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128b2d0)
Location: fs/select.c:210
Inline: True
```
**Symbols:**

```
ffffffff8128b2d0-ffffffff8128b359: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b1a90)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812b1a90-ffffffff812b1b18: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c6bb0)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812c6bb0-ffffffff812c6c38: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e3730)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812e3730-ffffffff812e37b8: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f5170)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812f5170-ffffffff812f51f8: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132d530)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff8132d530-ffffffff8132d5b8: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81338cb0)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff81338cb0-ffffffff81338d38: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133f340)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff8133f340-ffffffff8133f3c8: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138ccd0)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff8138ccd0-ffffffff8138cd58: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140dfc0)
Location: fs/select.c:211
Inline: False
```
**Symbols:**

```
ffffffff8140dfc0-ffffffff8140e054: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81498b00)
Location: fs/select.c:211
Inline: False
```
**Symbols:**

```
ffffffff81498b00-ffffffff81498b94: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814cdba0)
Location: fs/select.c:211
Inline: False
```
**Symbols:**

```
ffffffff814cdba0-ffffffff814cdc34: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff815004e0)
Location: fs/select.c:211
Inline: False
```
**Symbols:**

```
ffffffff815004e0-ffffffff81500574: pollwake (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a1d10)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffff8000103a1d10-ffff8000103a1dd0: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0584a64)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
c0584a64-c0584b10: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049be00)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
c00000000049be00-c00000000049bec0: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026a986)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffe00026a986-ffffffe00026aa0a: pollwake (STB_LOCAL)
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
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ed750)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812ed750-ffffffff812ed7d8: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812de380)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812de380-ffffffff812de408: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eb560)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812eb560-ffffffff812eb5e8: pollwake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pollwake(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fc550)
Location: fs/select.c:210
Inline: False
```
**Symbols:**

```
ffffffff812fc550-ffffffff812fc5d8: pollwake (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>wait_queue_t *wait</code> ➡️ <code>wait_queue_entry_t *wait</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
