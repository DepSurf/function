# Function: <code>ipc_findkey</code>

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
In ipc/util.c (ffffffff81325069)
Location: ipc/util.c:152
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff81359c59)
Location: ipc/util.c:152
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff81370139)
Location: ipc/util.c:152
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff81383525)
Location: ipc/util.c:152
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff813a78ef)
Location: ipc/util.c:175
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff813d6cdc)
Location: ipc/util.c:179
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff813f12d9)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff8141d57c)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff814373cc)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81486640)
Location: ipc/util.c:171
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff81486640-ffffffff8148675b: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a3c20)
Location: ipc/util.c:171
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff814a3c20-ffffffff814a3d34: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a9c20)
Location: ipc/util.c:171
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff814a9c20-ffffffff814a9d2c: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff815020d0)
Location: ipc/util.c:172
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff815020d0-ffffffff815021dc: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff815936f0)
Location: ipc/util.c:172
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff815936f0-ffffffff81593819: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163c140)
Location: ipc/util.c:172
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff8163c140-ffffffff8163c269: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816746e0)
Location: ipc/util.c:172
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff816746e0-ffffffff8167483b: ipc_findkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kern_ipc_perm *ipc_findkey(struct ipc_ids *ids, key_t key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b0aa0)
Location: ipc/util.c:172
Inline: False
Direct callers:
  - ipc/util.c:ipcget
```
**Symbols:**

```
ffffffff816b0aa0-ffffffff816b0bfb: ipc_findkey (STB_LOCAL)
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
In ipc/util.c (ffff80001051dbd0)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (c06da020)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (c000000000666f9c)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffe0003853e2)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff8142f9ac)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff8142042c)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff8142bb4c)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
In ipc/util.c (ffffffff81442b61)
Location: ipc/util.c:171
Inline: True
Inline callers:
  - ipc/util.c:ipcget
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
