# ADM Recruiting

Today's recruiting experiences an accelerated use of automatic decision making (ADM) systems. These systems shall help to find to find the right candidate for the job. The approach is not limited to application-type inputs, but is also used by headhunters to crawl professional social networks. Apart from an automated machine support for these tasks, recruiters often connect the hope to impartially (unbiased?) find the perfect match.

## Research Objective

We want to understand the area where the decisions results of ADM systems and recruiters overlap. In particular, we are interested in the effect of an ADM's assessment about an applicant on a recruiter, if the ADM's verdict is known to this recruiter.

As a result, we provide a first model to generate hypotheseses to be validated in future empirical research.

## Results

link to notebook `recruiting_model.ipynb`

## Quickstart

Start in project's root dir. Create docker image

```bash
docker-compose build r-bayes
```

Spin up the container and get a shell from the container
```bash
docker-compose up -d r-bayes
```

Point your browser to http://localhost:8008/ and load the notebook `recruiting_model.ipynb`
