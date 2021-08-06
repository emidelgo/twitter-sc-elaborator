# Twitter SC Elaborator
Twitter SC Elaborator is a Command Line Application written in Python. 

Binaries can be download from page https://github.com/emidelgo/twitter-sc-elaborator/releases.

The application is able to process data from Twitter in [JSON Lines](https://jsonlines.org) format, with tweets' JSON matching the original [Twitter tweet object](https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/tweet). It generates 3 xlsx files: one with the tweets, one with users stats and information, one with a adjacency matrix of tokens co-occuring in the same tweet. An applicative example is in this paper: XXXXX


# Getting started

Unzip the package you downloaded from release page. From the Command Line run 
``
twitter_sc_elaborator.exe generate:userstatsmatrix --help
``
to get information about the options to run the program.


Typical execution command is:

``
twitter_sc_elaborator.exe generate:userstatsmatrix --input_files_paths "pathToFile.jsonl.gz" --output output.xlsx --min-occurrences 5
``

# License

Copyright (c) 2021, Emiliano del Gobbo
All rights reserved.
Author Website: https://www.emilianodelgobbo.com
Project Website: https://github.com/emidelgo/twitter-sc-elaborator

You can't use, distribute or do any other action without explicit and
personal authorization of the author.

It's forbidden every type of reverse engineering of the binaries and artifacts.

THIS SOFTWARE IS PROVIDED BY Emiliano del Gobbo ''AS IS'' AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL Emiliano del Gobbo BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
