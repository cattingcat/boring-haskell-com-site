docker build -t boring-haskell-com .
docker run -d -p 8899:80 --name boring-haskell-com boring-haskell-com
