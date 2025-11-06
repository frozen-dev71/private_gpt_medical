# Changelog

## 0.0.1 (2025-11-06)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/frozen-dev71/private_gpt_medical/issues/1426)) ([9adc620](https://github.com/frozen-dev71/private_gpt_medical/commit/9adc6209ac129f01cddc9d3a8936c11ec02993f7))
* Add stream information to generate SDKs ([#1569](https://github.com/frozen-dev71/private_gpt_medical/issues/1569)) ([b3b06fa](https://github.com/frozen-dev71/private_gpt_medical/commit/b3b06fa54993473c54b78436657968fe1d443a9a))
* **API:** Ingest plain text ([#1417](https://github.com/frozen-dev71/private_gpt_medical/issues/1417)) ([f7cba78](https://github.com/frozen-dev71/private_gpt_medical/commit/f7cba78603b0ef35bf2edd1eda383c276f1d21a9))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/frozen-dev71/private_gpt_medical/issues/1432)) ([3f02754](https://github.com/frozen-dev71/private_gpt_medical/commit/3f02754d988761bb515450d11790bbd743ed758c))
* bump dependencies ([#1987](https://github.com/frozen-dev71/private_gpt_medical/issues/1987)) ([0bc6498](https://github.com/frozen-dev71/private_gpt_medical/commit/0bc6498d64e7c2c68735d459975eefa76cb96b97))
* **code:** improve concat of strings in ui ([#1785](https://github.com/frozen-dev71/private_gpt_medical/issues/1785)) ([6c88835](https://github.com/frozen-dev71/private_gpt_medical/commit/6c88835b9972b3e88aeee1ffdae71ca2870f5715))
* Disable Gradio Analytics ([#1165](https://github.com/frozen-dev71/private_gpt_medical/issues/1165)) ([a07614e](https://github.com/frozen-dev71/private_gpt_medical/commit/a07614e681a1267073ba5bc79feda204c66790aa))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/frozen-dev71/private_gpt_medical/issues/1812)) ([abeece5](https://github.com/frozen-dev71/private_gpt_medical/commit/abeece59538e73e28e942e182823a1221b32a203))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/frozen-dev71/private_gpt_medical/issues/1782)) ([95c284a](https://github.com/frozen-dev71/private_gpt_medical/commit/95c284a5dbb056e6f18e072757499b4d585d0d7e))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/frozen-dev71/private_gpt_medical/issues/1924)) ([4868035](https://github.com/frozen-dev71/private_gpt_medical/commit/48680359b5e0921cfdf0954da6ac008b6679d0dd))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/frozen-dev71/private_gpt_medical/issues/1741)) ([f0fbc56](https://github.com/frozen-dev71/private_gpt_medical/commit/f0fbc56d15df711e07e4c8fd33748a41c792acf5))
* **docs:** Fix setup docu ([#1926](https://github.com/frozen-dev71/private_gpt_medical/issues/1926)) ([7bf050e](https://github.com/frozen-dev71/private_gpt_medical/commit/7bf050e5d07dbca0f7458a0ed2d206224871ab0b))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/frozen-dev71/private_gpt_medical/issues/1968)) ([0324f17](https://github.com/frozen-dev71/private_gpt_medical/commit/0324f179f45b1ffccc0bacc030b2a2c88cde7707))
* **docs:** upgrade fern ([#1596](https://github.com/frozen-dev71/private_gpt_medical/issues/1596)) ([0d5a926](https://github.com/frozen-dev71/private_gpt_medical/commit/0d5a92674e0629b711aed79b5598881781bb84a1))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/frozen-dev71/private_gpt_medical/issues/1133)) ([c4dff77](https://github.com/frozen-dev71/private_gpt_medical/commit/c4dff77b1776e7796f13d154b74a9bb639a403ea))
* enable resume download for hf_hub_download ([#1249](https://github.com/frozen-dev71/private_gpt_medical/issues/1249)) ([dd1cb27](https://github.com/frozen-dev71/private_gpt_medical/commit/dd1cb272564f3f540335cafc7858c958318d67f6))
* Get answers using preferred number of chunks ([2313357](https://github.com/frozen-dev71/private_gpt_medical/commit/23133578a5eeb9836b19bb5deab72034b4b0c3eb))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/frozen-dev71/private_gpt_medical/issues/1750)) ([a3d8c60](https://github.com/frozen-dev71/private_gpt_medical/commit/a3d8c607a63c4468d2a5be0e06d542cb8da5b9c7))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/frozen-dev71/private_gpt_medical/issues/1698)) ([bd9c30d](https://github.com/frozen-dev71/private_gpt_medical/commit/bd9c30d79e4494720d03b072add02b3bf974a54d))
* **llm:** Add openailike llm mode ([#1447](https://github.com/frozen-dev71/private_gpt_medical/issues/1447)) ([b2b8ffd](https://github.com/frozen-dev71/private_gpt_medical/commit/b2b8ffd4803f1484df1a58d61dff129c696fc3a2)), closes [#1424](https://github.com/frozen-dev71/private_gpt_medical/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/frozen-dev71/private_gpt_medical/issues/1526)) ([a4a96e1](https://github.com/frozen-dev71/private_gpt_medical/commit/a4a96e18bdc565f573ac0874aff2b76752550156))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/frozen-dev71/private_gpt_medical/issues/1703)) ([3938c0c](https://github.com/frozen-dev71/private_gpt_medical/commit/3938c0ccf7afdeb2859b2269fcdbce85f43d415f))
* **llm:** drop default_system_prompt ([#1385](https://github.com/frozen-dev71/private_gpt_medical/issues/1385)) ([e8dd922](https://github.com/frozen-dev71/private_gpt_medical/commit/e8dd9225b0095a81dba8b28f710464a0a723c0e5))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/frozen-dev71/private_gpt_medical/issues/1800)) ([a68e2df](https://github.com/frozen-dev71/private_gpt_medical/commit/a68e2df27d9aa26ba188671cb16141f77a0cb939))
* **llm:** Ollama timeout setting ([#1773](https://github.com/frozen-dev71/private_gpt_medical/issues/1773)) ([012526a](https://github.com/frozen-dev71/private_gpt_medical/commit/012526ae3abaaf895e96e3e94e0dc4c53e4dc745))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/frozen-dev71/private_gpt_medical/issues/1965)) ([6af99a5](https://github.com/frozen-dev71/private_gpt_medical/commit/6af99a57706804bc09562df24e52301e84f7d8d2))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/frozen-dev71/private_gpt_medical/issues/1467)) ([061319b](https://github.com/frozen-dev71/private_gpt_medical/commit/061319b95cd4f035cd86631f6672aa85af740bf2))
* move torch and transformers to local group ([#1172](https://github.com/frozen-dev71/private_gpt_medical/issues/1172)) ([fdf56b2](https://github.com/frozen-dev71/private_gpt_medical/commit/fdf56b2f2387863d88a8da7f9e832fe058a6dfab))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/frozen-dev71/private_gpt_medical/issues/1706)) ([33ac326](https://github.com/frozen-dev71/private_gpt_medical/commit/33ac326bd2264949559fc24aedf2e6494fdf3eb5))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/frozen-dev71/private_gpt_medical/issues/1835)) ([e5f9339](https://github.com/frozen-dev71/private_gpt_medical/commit/e5f9339479071e8143e07542c7e53eb3e3017823))
* Qdrant support ([#1228](https://github.com/frozen-dev71/private_gpt_medical/issues/1228)) ([789f9ef](https://github.com/frozen-dev71/private_gpt_medical/commit/789f9efaf3efd7f22842ad1e591b522a445088b0))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/frozen-dev71/private_gpt_medical/issues/1771)) ([714eb81](https://github.com/frozen-dev71/private_gpt_medical/commit/714eb8110912950d934f9f6f738843baafea78f0))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/frozen-dev71/private_gpt_medical/issues/1810)) ([051e0e1](https://github.com/frozen-dev71/private_gpt_medical/commit/051e0e1e7e1c88046aaa06a3bd8ec7eb5630d270))
* Release GitHub action ([#1078](https://github.com/frozen-dev71/private_gpt_medical/issues/1078)) ([d7fdf4e](https://github.com/frozen-dev71/private_gpt_medical/commit/d7fdf4ea553cb13e012ef60654beeaacc01d39e8))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/frozen-dev71/private_gpt_medical/issues/1783)) ([ce1f27d](https://github.com/frozen-dev71/private_gpt_medical/commit/ce1f27da791eccefa35c0ef943a9f191e1427732))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/frozen-dev71/private_gpt_medical/issues/1437)) ([48134ed](https://github.com/frozen-dev71/private_gpt_medical/commit/48134ed6f6342cd77f8288049097d72328862f43))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/frozen-dev71/private_gpt_medical/issues/1415)) ([f0d1be1](https://github.com/frozen-dev71/private_gpt_medical/commit/f0d1be1c5b2440abacf7bc1a200eb5f30e309c80))
* **ui:** add LLM mode to UI ([#1080](https://github.com/frozen-dev71/private_gpt_medical/issues/1080)) ([14e2f62](https://github.com/frozen-dev71/private_gpt_medical/commit/14e2f62b4fafce986a4827e14cf33db0e7e515ee))
* **ui:** Add Model Information to ChatInterface label ([030c856](https://github.com/frozen-dev71/private_gpt_medical/commit/030c856967be78cb3b5827f184f47b697746ab10))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/frozen-dev71/private_gpt_medical/issues/1705)) ([734673e](https://github.com/frozen-dev71/private_gpt_medical/commit/734673e03ab5f62adb91777a6c2a13b2299fb1f3))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/frozen-dev71/private_gpt_medical/issues/1353)) ([f9ce966](https://github.com/frozen-dev71/private_gpt_medical/commit/f9ce966a85ad38a488175af553625ccc1f9220cc))
* **UI:** Faster startup and document listing ([#1763](https://github.com/frozen-dev71/private_gpt_medical/issues/1763)) ([bdcac55](https://github.com/frozen-dev71/private_gpt_medical/commit/bdcac553da9de9dbd416b002f3f9550177d3488c))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/frozen-dev71/private_gpt_medical/issues/1643)) ([489b453](https://github.com/frozen-dev71/private_gpt_medical/commit/489b453c868c37024be52d91129434a1f4d05b65))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/frozen-dev71/private_gpt_medical/issues/1397)) ([cb7e3e5](https://github.com/frozen-dev71/private_gpt_medical/commit/cb7e3e517ca59b0a25885f6f7e6fec99f33eaf6e))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/frozen-dev71/private_gpt_medical/issues/1612)) ([db499b3](https://github.com/frozen-dev71/private_gpt_medical/commit/db499b3a64e13ac8affec4541e4a51582fe3f537))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/frozen-dev71/private_gpt_medical/issues/1730)) ([070b8f5](https://github.com/frozen-dev71/private_gpt_medical/commit/070b8f52d3934f7a3e62412e921079e72fb43e20))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/frozen-dev71/private_gpt_medical/issues/1663)) ([934e923](https://github.com/frozen-dev71/private_gpt_medical/commit/934e923123c289676c0399621247ebcb02d41542))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/frozen-dev71/private_gpt_medical/issues/1883)) ([33f4601](https://github.com/frozen-dev71/private_gpt_medical/commit/33f460103fecf5804f867d899ae2a11fd0cdc6f9))
* **Vector:** support pgvector ([#1624](https://github.com/frozen-dev71/private_gpt_medical/issues/1624)) ([6e0303b](https://github.com/frozen-dev71/private_gpt_medical/commit/6e0303b8109b1c8bcbf556cc1066e411ac74a167))
* wipe per storage type ([#1772](https://github.com/frozen-dev71/private_gpt_medical/issues/1772)) ([9d8dfa7](https://github.com/frozen-dev71/private_gpt_medical/commit/9d8dfa71c911320361d0aaabe1aeec0dd03bf9bf))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/frozen-dev71/private_gpt_medical/issues/1841)) ([d1657fe](https://github.com/frozen-dev71/private_gpt_medical/commit/d1657fe6c1b3b0521309c6005caa8e3e2bb3ad54))
* 294 (tested) ([9a29d53](https://github.com/frozen-dev71/private_gpt_medical/commit/9a29d53e2c01db20c64e59eb011ecc8f41ed56c0))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([438f4ea](https://github.com/frozen-dev71/private_gpt_medical/commit/438f4ea896c8795f28254d2e922048e0117a71b0))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/frozen-dev71/private_gpt_medical/issues/1519)) ([9e7b1c9](https://github.com/frozen-dev71/private_gpt_medical/commit/9e7b1c939d9444499b66e7b1ca60cf0c72e707de))
* chromadb max batch size ([#1087](https://github.com/frozen-dev71/private_gpt_medical/issues/1087)) ([78c4da5](https://github.com/frozen-dev71/private_gpt_medical/commit/78c4da593bf591b6dae1b1a3b62d6f4a7d8d0826))
* **deploy:** fix local and external dockerfiles ([c23181a](https://github.com/frozen-dev71/private_gpt_medical/commit/c23181a4f2322d5a0a9b4faaee8f03d909e373af))
* Disable Chroma Telemetry ([fdf786a](https://github.com/frozen-dev71/private_gpt_medical/commit/fdf786afaf87ee36413c1cbdc3fcdacf9cabca70))
* Docker and sagemaker setup ([#1118](https://github.com/frozen-dev71/private_gpt_medical/issues/1118)) ([60e8a1e](https://github.com/frozen-dev71/private_gpt_medical/commit/60e8a1e335633cda38fdd560342c4ed18d6aeaed))
* **docker:** docker broken copy ([#1419](https://github.com/frozen-dev71/private_gpt_medical/issues/1419)) ([e6f32db](https://github.com/frozen-dev71/private_gpt_medical/commit/e6f32dbf84331a7f5ea0b7bfa36d040563d871f2))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/frozen-dev71/private_gpt_medical/issues/1779)) ([da6ccde](https://github.com/frozen-dev71/private_gpt_medical/commit/da6ccde75ea41aaa2adc958a96da0ae88d91e093))
* **docs:** Minor documentation amendment ([#1739](https://github.com/frozen-dev71/private_gpt_medical/issues/1739)) ([324b633](https://github.com/frozen-dev71/private_gpt_medical/commit/324b633bffe4b6371da9e259a8c314a5712de718))
* **docs:** Update installation.mdx ([#1866](https://github.com/frozen-dev71/private_gpt_medical/issues/1866)) ([146a019](https://github.com/frozen-dev71/private_gpt_medical/commit/146a01975c91a52de9ca5b8fcaefacd5ed76aeb0))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([684b01d](https://github.com/frozen-dev71/private_gpt_medical/commit/684b01d255c07e4880d89627167dafd36389fd17))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/frozen-dev71/private_gpt_medical/issues/1123)) ([63bf579](https://github.com/frozen-dev71/private_gpt_medical/commit/63bf579dc6c37a978e616db85cef40de740eb430))
* Fixed docker-compose ([#1758](https://github.com/frozen-dev71/private_gpt_medical/issues/1758)) ([738c80e](https://github.com/frozen-dev71/private_gpt_medical/commit/738c80ead105b8659965233a661251ab54e9b3d9))
* **ingest:** update script label ([#1770](https://github.com/frozen-dev71/private_gpt_medical/issues/1770)) ([307ac6e](https://github.com/frozen-dev71/private_gpt_medical/commit/307ac6eb451680b441268abe648f9386490c8734))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/frozen-dev71/private_gpt_medical/issues/1954)) ([4a6f2b1](https://github.com/frozen-dev71/private_gpt_medical/commit/4a6f2b1cf0b698828c652548d4e83013514bdb06))
* **llm:** special tokens and leading space ([#1831](https://github.com/frozen-dev71/private_gpt_medical/issues/1831)) ([3393eb4](https://github.com/frozen-dev71/private_gpt_medical/commit/3393eb4a5ea2d12289addcc3f6be8ffdc9063a10))
* make docs more visible ([#1081](https://github.com/frozen-dev71/private_gpt_medical/issues/1081)) ([849dc88](https://github.com/frozen-dev71/private_gpt_medical/commit/849dc88a23df7de9c06bb4bed4d9224659bfac9d))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/frozen-dev71/private_gpt_medical/issues/1859)) ([4b7a915](https://github.com/frozen-dev71/private_gpt_medical/commit/4b7a91531758d9a9d43827e6b66c92cb9efa8051))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/frozen-dev71/private_gpt_medical/issues/1449)) ([1a9303f](https://github.com/frozen-dev71/private_gpt_medical/commit/1a9303f2bacde2ced5a342866f7fff9130a91e82))
* Remove global state ([#1216](https://github.com/frozen-dev71/private_gpt_medical/issues/1216)) ([eefc1ec](https://github.com/frozen-dev71/private_gpt_medical/commit/eefc1ec21c416881a9d5c6ad520238cb2c522efd))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/frozen-dev71/private_gpt_medical/issues/1890)) ([333fc1a](https://github.com/frozen-dev71/private_gpt_medical/commit/333fc1a259de4e62e1c0131ace7ec7e85cf1321b))
* sagemaker config and chat methods ([#1142](https://github.com/frozen-dev71/private_gpt_medical/issues/1142)) ([4baf2a1](https://github.com/frozen-dev71/private_gpt_medical/commit/4baf2a1898215ceaaaf6776ef9212813f4cf9564))
* **settings:** correct yaml multiline string ([#1403](https://github.com/frozen-dev71/private_gpt_medical/issues/1403)) ([e0a7d32](https://github.com/frozen-dev71/private_gpt_medical/commit/e0a7d32067cb88646424e5ec16f8596b90291be2))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/frozen-dev71/private_gpt_medical/issues/1925)) ([f8b7407](https://github.com/frozen-dev71/private_gpt_medical/commit/f8b7407fd081fdcf096f6345d92e69078a49e66b))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/frozen-dev71/private_gpt_medical/issues/1709)) ([3e091a9](https://github.com/frozen-dev71/private_gpt_medical/commit/3e091a9be714652ba11f9622c8de91dfd7f01d85))
* **tests:** load the test settings only when running tests ([b14e6a3](https://github.com/frozen-dev71/private_gpt_medical/commit/b14e6a3ece4b83ede648e391c7036340bb71cde0))
* typo in README.md ([#1091](https://github.com/frozen-dev71/private_gpt_medical/issues/1091)) ([c6fb23d](https://github.com/frozen-dev71/private_gpt_medical/commit/c6fb23d93834139ff37f03e857a24c3f0b78ed78))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([bec5eee](https://github.com/frozen-dev71/private_gpt_medical/commit/bec5eee2ba1a2fef4c46440c08d00dc7ea211a3f))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/frozen-dev71/private_gpt_medical/issues/1260)) ([60ee344](https://github.com/frozen-dev71/private_gpt_medical/commit/60ee344fcfdacc5c5ffcc340a1cf93cc416144f1))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/frozen-dev71/private_gpt_medical/issues/1280)) ([309255f](https://github.com/frozen-dev71/private_gpt_medical/commit/309255f7b591d5757751fd769ce32e639fdb13a1))


### Miscellaneous Chores

* Initial version ([5e2d27a](https://github.com/frozen-dev71/private_gpt_medical/commit/5e2d27a90924fd38feafa2fe947a96fbe5af6054))

## [0.5.0](https://github.com/zylon-ai/private-gpt/compare/v0.4.0...v0.5.0) (2024-04-02)


### Features

* **code:** improve concat of strings in ui ([#1785](https://github.com/zylon-ai/private-gpt/issues/1785)) ([bac818a](https://github.com/zylon-ai/private-gpt/commit/bac818add51b104cda925b8f1f7b51448e935ca1))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/zylon-ai/private-gpt/issues/1812)) ([f83abff](https://github.com/zylon-ai/private-gpt/commit/f83abff8bc955a6952c92cc7bcb8985fcec93afa))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/zylon-ai/private-gpt/issues/1782)) ([8a836e4](https://github.com/zylon-ai/private-gpt/commit/8a836e4651543f099c59e2bf497ab8c55a7cd2e5))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/zylon-ai/private-gpt/issues/1741)) ([5725181](https://github.com/zylon-ai/private-gpt/commit/572518143ac46532382db70bed6f73b5082302c1))
* **docs:** upgrade fern ([#1596](https://github.com/zylon-ai/private-gpt/issues/1596)) ([84ad16a](https://github.com/zylon-ai/private-gpt/commit/84ad16af80191597a953248ce66e963180e8ddec))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/zylon-ai/private-gpt/issues/1750)) ([134fc54](https://github.com/zylon-ai/private-gpt/commit/134fc54d7d636be91680dc531f5cbe2c5892ac56))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/zylon-ai/private-gpt/issues/1698)) ([1efac6a](https://github.com/zylon-ai/private-gpt/commit/1efac6a3fe19e4d62325e2c2915cd84ea277f04f))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/zylon-ai/private-gpt/issues/1703)) ([02dc83e](https://github.com/zylon-ai/private-gpt/commit/02dc83e8e9f7ada181ff813f25051bbdff7b7c6b))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/zylon-ai/private-gpt/issues/1800)) ([b3b0140](https://github.com/zylon-ai/private-gpt/commit/b3b0140e244e7a313bfaf4ef10eb0f7e4192710e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/zylon-ai/private-gpt/issues/1773)) ([6f6c785](https://github.com/zylon-ai/private-gpt/commit/6f6c785dac2bbad37d0b67fda215784298514d39))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/zylon-ai/private-gpt/issues/1467)) ([821bca3](https://github.com/zylon-ai/private-gpt/commit/821bca32e9ee7c909fd6488445ff6a04463bf91b))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/zylon-ai/private-gpt/issues/1706)) ([68b3a34](https://github.com/zylon-ai/private-gpt/commit/68b3a34b032a08ca073a687d2058f926032495b3))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/zylon-ai/private-gpt/issues/1771)) ([087cb0b](https://github.com/zylon-ai/private-gpt/commit/087cb0b7b74c3eb80f4f60b47b3a021c81272ae1))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/zylon-ai/private-gpt/issues/1810)) ([83adc12](https://github.com/zylon-ai/private-gpt/commit/83adc12a8ef0fa0c13a0dec084fa596445fc9075))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/zylon-ai/private-gpt/issues/1783)) ([ea153fb](https://github.com/zylon-ai/private-gpt/commit/ea153fb92f1f61f64c0d04fff0048d4d00b6f8d0))
* **ui:** Add Model Information to ChatInterface label ([f0b174c](https://github.com/zylon-ai/private-gpt/commit/f0b174c097c2d5e52deae8ef88de30a0d9013a38))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/zylon-ai/private-gpt/issues/1705)) ([290b9fb](https://github.com/zylon-ai/private-gpt/commit/290b9fb084632216300e89bdadbfeb0380724b12))
* **UI:** Faster startup and document listing ([#1763](https://github.com/zylon-ai/private-gpt/issues/1763)) ([348df78](https://github.com/zylon-ai/private-gpt/commit/348df781b51606b2f9810bcd46f850e54192fd16))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/zylon-ai/private-gpt/issues/1643)) ([410bf7a](https://github.com/zylon-ai/private-gpt/commit/410bf7a71f17e77c4aec723ab80c233b53765964))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/zylon-ai/private-gpt/issues/1730)) ([63de7e4](https://github.com/zylon-ai/private-gpt/commit/63de7e4930ac90dd87620225112a22ffcbbb31ee))
* wipe per storage type ([#1772](https://github.com/zylon-ai/private-gpt/issues/1772)) ([c2d6948](https://github.com/zylon-ai/private-gpt/commit/c2d694852b4696834962a42fde047b728722ad74))


### Bug Fixes

* **docs:** Minor documentation amendment ([#1739](https://github.com/zylon-ai/private-gpt/issues/1739)) ([258d02d](https://github.com/zylon-ai/private-gpt/commit/258d02d87c5cb81d6c3a6f06aa69339b670dffa9))
* Fixed docker-compose ([#1758](https://github.com/zylon-ai/private-gpt/issues/1758)) ([774e256](https://github.com/zylon-ai/private-gpt/commit/774e2560520dc31146561d09a2eb464c68593871))
* **ingest:** update script label ([#1770](https://github.com/zylon-ai/private-gpt/issues/1770)) ([7d2de5c](https://github.com/zylon-ai/private-gpt/commit/7d2de5c96fd42e339b26269b3155791311ef1d08))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/zylon-ai/private-gpt/issues/1709)) ([d17c34e](https://github.com/zylon-ai/private-gpt/commit/d17c34e81a84518086b93605b15032e2482377f7))

## [0.4.0](https://github.com/imartinez/privateGPT/compare/v0.3.0...v0.4.0) (2024-03-06)


### Features

* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/imartinez/privateGPT/issues/1663)) ([45f0571](https://github.com/imartinez/privateGPT/commit/45f05711eb71ffccdedb26f37e680ced55795d44))
* **Vector:** support pgvector ([#1624](https://github.com/imartinez/privateGPT/issues/1624)) ([cd40e39](https://github.com/imartinez/privateGPT/commit/cd40e3982b780b548b9eea6438c759f1c22743a8))

## [0.3.0](https://github.com/imartinez/privateGPT/compare/v0.2.0...v0.3.0) (2024-02-16)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/imartinez/privateGPT/issues/1426)) ([e326126](https://github.com/imartinez/privateGPT/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* Add stream information to generate SDKs ([#1569](https://github.com/imartinez/privateGPT/issues/1569)) ([24fae66](https://github.com/imartinez/privateGPT/commit/24fae660e6913aac6b52745fb2c2fe128ba2eb79))
* **API:** Ingest plain text ([#1417](https://github.com/imartinez/privateGPT/issues/1417)) ([6eeb95e](https://github.com/imartinez/privateGPT/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/imartinez/privateGPT/issues/1432)) ([b178b51](https://github.com/imartinez/privateGPT/commit/b178b514519550e355baf0f4f3f6beb73dca7df2))
* **llm:** Add openailike llm mode ([#1447](https://github.com/imartinez/privateGPT/issues/1447)) ([2d27a9f](https://github.com/imartinez/privateGPT/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/imartinez/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/imartinez/privateGPT/issues/1526)) ([6bbec79](https://github.com/imartinez/privateGPT/commit/6bbec79583b7f28d9bea4b39c099ebef149db843))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/imartinez/privateGPT/issues/1437)) ([4780540](https://github.com/imartinez/privateGPT/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/imartinez/privateGPT/issues/1415)) ([8ec7cf4](https://github.com/imartinez/privateGPT/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/imartinez/privateGPT/issues/1397)) ([c71ae7c](https://github.com/imartinez/privateGPT/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/imartinez/privateGPT/issues/1612)) ([aa13afd](https://github.com/imartinez/privateGPT/commit/aa13afde07122f2ddda3942f630e5cadc7e4e1ee))


### Bug Fixes

* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/imartinez/privateGPT/issues/1519)) ([869233f](https://github.com/imartinez/privateGPT/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/imartinez/privateGPT/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* **docker:** docker broken copy ([#1419](https://github.com/imartinez/privateGPT/issues/1419)) ([059f358](https://github.com/imartinez/privateGPT/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/imartinez/privateGPT/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/imartinez/privateGPT/issues/1449)) ([6191bcd](https://github.com/imartinez/privateGPT/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* **settings:** correct yaml multiline string ([#1403](https://github.com/imartinez/privateGPT/issues/1403)) ([2564f8d](https://github.com/imartinez/privateGPT/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/imartinez/privateGPT/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([24fb80c](https://github.com/imartinez/privateGPT/commit/24fb80ca38f21910fe4fd81505d14960e9ed4faa))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
