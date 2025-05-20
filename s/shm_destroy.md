# Function: <code>shm_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81329f30)
Location: ipc/shm.c:228
Inline: False
Direct callers:
  - ipc/shm.c:shm_close
  - ipc/shm.c:exit_shm
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81329f30-ffffffff8132a005: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8135ebc0)
Location: ipc/shm.c:228
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8135ebc0-ffffffff8135ec95: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813753c0)
Location: ipc/shm.c:229
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff813753c0-ffffffff81375495: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81388f60)
Location: ipc/shm.c:230
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81388f60-ffffffff81389040: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813adcb0)
Location: ipc/shm.c:233
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff813adcb0-ffffffff813add90: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813dde60)
Location: ipc/shm.c:261
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff813dde60-ffffffff813ddf78: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f84e0)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff813f84e0-ffffffff813f85f8: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814249f0)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814249f0-ffffffff81424b0c: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143e740)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8143e740-ffffffff8143e85c: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148f0a0)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8148f0a0-ffffffff8148f1bc: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ac770)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814ac770-ffffffff814ac891: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b2610)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814b2610-ffffffff814b2731: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150abb0)
Location: ipc/shm.c:322
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8150abb0-ffffffff8150ad10: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159c6a0)
Location: ipc/shm.c:322
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8159c6a0-ffffffff8159c7ea: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81645b10)
Location: ipc/shm.c:328
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
```
**Symbols:**

```
ffffffff81645b10-ffffffff81645c5a: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167e020)
Location: ipc/shm.c:328
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
```
**Symbols:**

```
ffffffff8167e020-ffffffff8167e16d: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816ba410)
Location: ipc/shm.c:329
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:__shm_close
```
**Symbols:**

```
ffffffff816ba410-ffffffff816ba55d: shm_destroy (STB_LOCAL)
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
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff8000105262f0)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffff8000105262f0-ffff8000105263f0: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e0374)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
c06e0374-c06e044c: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000670fa0)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
c000000000670fa0-c00000000067115c: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffe00038a7fc)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffe00038a7fc-ffffffe00038a926: shm_destroy (STB_LOCAL)
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
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81436d20)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81436d20-ffffffff81436e3c: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81427790)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81427790-ffffffff814278ac: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81432ec0)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81432ec0-ffffffff81432fdc: shm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shm_destroy(struct ipc_namespace *ns, struct shmid_kernel *shp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144a370)
Location: ipc/shm.c:279
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8144a370-ffffffff8144a48f: shm_destroy (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
