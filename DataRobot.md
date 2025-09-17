We need this fork to resolve the licence issue blocking us from further progress with the Milvus integration.

Before deleting the fork, the only thing that needs to be done is to replace the problematic `ujson` library, which has a "government use" clause in its licence, with the better alternative `orjson`, which has no licence issues.
