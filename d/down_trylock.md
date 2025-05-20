# Function: <code>down_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810c9cf0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810c9cf0-ffffffff810c9d28: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810ce670)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810ce670-ffffffff810ce6a8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810d52b0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810d52b0-ffffffff810d52e8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810d4280)
Location: kernel/locking/semaphore.c:131
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810d4280-ffffffff810d42b8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810dc1e0)
Location: kernel/locking/semaphore.c:131
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810dc1e0-ffffffff810dc218: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810e4820)
Location: kernel/locking/semaphore.c:131
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810e4820-ffffffff810e4858: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810efe10)
Location: kernel/locking/semaphore.c:131
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810efe10-ffffffff810efe48: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810f7860)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810f7860-ffffffff810f7898: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81103690)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81103690-ffffffff811036c8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110e1f0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - fs/pstore/platform.c:pstore_dump
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8110e1f0-ffffffff8110e228: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110b4b0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - fs/pstore/platform.c:pstore_dump
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_nonblocking
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8110b4b0-ffffffff8110b4e8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8110d2d0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - fs/pstore/platform.c:pstore_dump
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8110d2d0-ffffffff8110d308: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8112cb00)
Location: kernel/locking/semaphore.c:133
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - fs/pstore/platform.c:pstore_dump
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8112cb00-ffffffff8112cb38: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff8114dd60)
Location: kernel/locking/semaphore.c:134
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff8114dd60-ffffffff8114dda0: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff820d0210)
Location: kernel/locking/semaphore.c:134
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_trylock
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff820d0210-ffffffff820d0250: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff821545a0)
Location: kernel/locking/semaphore.c:134
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_trylock
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff821545a0-ffffffff821545e0: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff822373e0)
Location: kernel/locking/semaphore.c:134
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/firmware/efi/vars.c:efivar_trylock
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff822373e0-ffffffff82237420: down_trylock (STB_GLOBAL)
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
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffff800010168a10)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffff800010168a10-ffff800010168ab4: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (c03b4fd8)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
c03b4fd8-c03b5014: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (c0000000001c06f0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
c0000000001c06f0-c0000000001c0760: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffe00010a5a2)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffe00010a5a2-ffffffe00010a5f2: down_trylock (STB_GLOBAL)
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
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810fc9a0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810fc9a0-ffffffff810fc9d8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810ecbb0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810ecbb0-ffffffff810ecbe8: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff810f9b60)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff810f9b60-ffffffff810f9b98: down_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int down_trylock(struct semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/semaphore.c (ffffffff81104cd0)
Location: kernel/locking/semaphore.c:130
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
  - net/core/netpoll.c:netpoll_poll_dev
```
**Symbols:**

```
ffffffff81104cd0-ffffffff81104d08: down_trylock (STB_GLOBAL)
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
