

getArticles() {
    return this.http.get('api/v1/articles)
        .then((res) => console.log(res))
        .catch((res) => console.log(res))
}

getArticles() {
    return this.http.get('api/v1/articles)
        .subscribe(
            res => console.log(res),
            err => console.log(err)
        )
}

getArticles() {
    return this.http.get('api/v1/articles)
        .toPromise()
        .then((res) => console.log(res))
        .catch((res) => console.log(res))
}

getArticles() {
    return this.http.get('api/v1/articles)
}

getArticles() {
    return this.http.get('api/v1/articles)
        .retryWhen(function () {
            
        })
        .subscribe(
            res => console.log(res),
            err => console.log(err)
        )
}
