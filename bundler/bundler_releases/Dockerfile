FROM rubybench/ruby:0.3
MAINTAINER Alan Guo Xiang Tan "https://twitter.com/tgx_world"

RUN git clone --verbose --branch master --single-branch https://github.com/ruby-bench/ruby-bench-suite.git

ADD runner runner
RUN chmod 755 runner

CMD /bin/bash -l -c "./runner"
