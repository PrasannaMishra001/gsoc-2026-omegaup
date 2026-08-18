# GSoC 2026: Cronjob Optimization for omegaUp

Final work report for Google Summer of Code 2026.

**Read it here: https://prasannamishra001.github.io/gsoc-2026-omegaup/**

Contributor: [Prasanna Mishra](https://github.com/PrasannaMishra001)
Organisation: [omegaUp](https://omegaup.com)
Mentors: [Juan Pablo](https://github.com/pabo99), [Ankit](https://github.com/Ankitsinghsisodya)

I built the layer that watches omegaUp's background jobs: a registry of every job, a
history of every run, a lock so two copies can never overlap, an admin dashboard, and a
rerun button that is safe to press. Two further projects, scheduled training for the
recommendation model and automated problem health checks, are built on top of it.

- [All my pull requests](https://github.com/omegaup/omegaup/pulls?q=is%3Apr+author%3APrasannaMishra001)
- [All my issues](https://github.com/omegaup/omegaup/issues?q=is%3Aissue+author%3APrasannaMishra001)
- [The epic that ties the main project together](https://github.com/omegaup/omegaup/issues/9992)
- [Progress tracker discussion](https://github.com/omegaup/omegaup/discussions/9972)
